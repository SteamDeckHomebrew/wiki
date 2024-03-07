---
title: The Steam Deck Dual Screen Project
description: A short write-up of a project to mount a second screen to the Steam Deck with touch support and easy removal, without 3D printing anything.
published: true
date: 2024-03-07T13:04:39.965Z
tags: homebrew, hardware
editor: markdown
dateCreated: 2024-03-07T11:36:12.779Z
---

# The Steam Deck Dual Screen Project | by *holly*

This is a project to mount a second screen to the Steam Deck for better 3DS/DS/WiiU emulation (amongst other things). I didn't use any personally 3D printed parts, though I believe one of the parts *can* be printed. The hardware section is fairly straight-forward, software a little less so.

I decided on this project as I personally haven't felt right emulating dual-screen consoles - it always felt wrong to display two virtual screens on one, or use two giant monitors several times the size to display them, and even worse to use a mouse to control the touchscreens. As the deck is a handheld, I thought it would be a decent idea to use it as a springboard for a more authentic experience with those systems.

## Hardware

This section is surprisingly simple. 

First off, we need a way to mount a new screen. I've seen multiple prints of mounts, each of varying quality, size and weight, but for this I decided on the [Mechanism Deckmate](https://getmechanism.com/) - specifically the phone mount bundle. The reason I chose this, is that the clip can be left on and the phone mount easily removed, to allow this to remain *very* easy to detatch. It's also pretty lightweight and sturdy enough, though the phone mount can wobble a little. 

Next, we need a screen. A good way to find a decent screen is to search for ones made for Raspberry Pi devices. The one I'm using it unfortunately one of those high-point Scrabble word names from Amazon, but my general rules were that it doesn't need to be high resolution, needs touch, and also importantly ***must have a backplate***.

The screen I settled on is a 7 inch 1024x600 IPS panel intended for a Raspberry Pi 4, that has a nice, strong shell and minimal bezels. It has a full shell, 3 extremely low profile OSD buttons and uses micro USB and a mini-HDMI port.

![img_20240307_115917_1.jpg](/wiki/dual-screen-project/img_20240307_115917_1.jpg)

We also need cables. For this, I used parts intended for FPV drones, which means generally barebones - PCB and ribbon cables! If the ports face to the side, we want to keep as much stress off them as possible. For my particular screen, the ports are ***extremely*** close together. The cables that came with it fit of course, but they stick out to the side and put a lot of stress on the ports when bent. Our barebones FPV cables with right angle connectors allow us to take almost all the stress off those ports and keep things minimal. For this screen, I needed a 90° micro USB connector, a 90° mini-HDMI connector, both ribbon cables, and needed them to end in a USB-A connector and a full-size HDMI connector respectively.

![img_20240307_115932_1.jpg](/wiki/dual-screen-project/img_20240307_115932_1.jpg)

As you can see, these lie pretty flush against the casing (orientation willing, this screen is a little *too* compact on the ports). These go into a standard USB-C hub, which has 3 ports - power delivery, HDMI and USB-A. Our screen plugs into the USB-A and HDMI ports, and the spare power delivery port allows us to charge the Steam Deck while playing - it's not necessary for the screen, the Steam Deck will power that itself. You'll need to measure out how long your hub cable needs to be, and also get a 180° USB-C adapter for the Deck in order to neatly keep the cable straight and behind the deck. I personally used nano tape to secure all of this to the back of the screen.

To attach the screen to the Deckmate phone mount, we want a small Magsafe ring. You can get these in loads of places, Amazon etc. This is why we needed the screen to have a shell, or at least a backplate. Alignment is a little tricky, and you probably need to unscrew the phone mount's magsafe portion to reverse it for further reach - [here is a timestamped link to Mechanism's video on how to do this](https://youtu.be/axkgBOhTh0s?t=118). Afterwards it should be as easy as magnets! This was an important step to allow us to keep things modular and usable on their own for other reasons.

Once all this is assembled, simply clip the phone mount onto the Deckmate! I very heavily recommend mounting the screen ***underneath***, for a few reasons.
- Mounting above means the Deck's vent blasts heat at the screen
- Mounting above is also very top heavy with a very unstable center of gravity
- The Steam Deck's internal screen is likely higher resolution, and thus makes more sense as the 3D screen

![img_20240307_122140_1.jpg](/wiki/dual-screen-project/img_20240307_122140_1.jpg)
![img_20240307_122128_1.jpg](/wiki/dual-screen-project/img_20240307_122128_1.jpg)

And we're done! Now we need to sort out software, as things were NOT simple.

## Software

This only works in desktop mode, so hop over to desktop mode. The Steam Deck should automatically pick up the new screen and ask what to do with it - click extend (in any direction). We then want to hop into display settings (you can right click the desktop to find this easily) and drag our new screen's position to make sense (above/below) and make sure it's rotated correctly. 

![orientation.png](/wiki/dual-screen-project/orientation.png)

Now, we get into where things *might* get difficult. For me and my choice of screen, touch was completely misaligned. Touches on the Deck's screen would result in the input being stretched across *both* panels, i.e - a touch at the top of the Deck's screen would register at the top of the Deck's screen, but touches at the *bottom* of the *Deck's screen* would register at the *bottom of the external panel*, and touches on the external panel would register rotated 90° on the *Deck's* panel. This obviously won't work!

Fixing this is unfortunately not simple. We need to install `xorg-xinput` using pacman, which in turn requires disabling SteamOS's read-only nature with `sudo steamos-readonly disable`. Because of this we have another caveat - these modifications get wiped on a SteamOS update. That's fine, we can just use a script to very quickly reinstall.

I have uploaded the scripts I use to [GitHub](https://github.com/HollyCeuin/3DSDeck-HardwareProject-Scripts) - they will almost definitely need modification for you though, specifically the line `xinput --map-to-output "<touch device>" "<display name>"`

Once you've installed xinput (take a look at the script on GitHub to figure out how), we need to run it and `xrandr` in order to figure out a couple things. We need to figure out what the new panel's touch input is named, and what the display is named. This is simple, fortunately - run `xinput` while the screen isn't plugged in, and take note of what's returned.

![xinput-without-screen.png](/wiki/dual-screen-project/xinput-without-screen.png)

As we can see, under "Virtual core pointer", without the screen plugged in, we have three entries. Time to plug the screen in.

![xinput-with-screen.png](/wiki/dual-screen-project/xinput-with-screen.png)

Now we have four entries. Perfect, we can see that (for me, yours will vary) the name we need is "wch.cn USB2IIC_CTP_CONTROL"

Now we need to run xrandr.

![xrandr.png](/wiki/dual-screen-project/xrandr.png)

Fortunately this one is most likely going to be the same for all of us - the internal monitor is named "eDP" and the external named "DisplayPort-0".

This makes our command to fix input (by mapping the new screen's touch input to the correct device):

`xinput --map-to-output "wch.cn USB2IIC_CTP_CONTROL" "DisplayPort-0"`

Run that command, and touch input should be aligned correctly. I recommend keeping both the install-xinput script and quickfix script on hand - as stated before, SteamOS updates will wipe xinput, and unplugging/replugging the screen or restarting the deck will mean you need to run the above line again. You can add this to the KDE autostart entries if you want, but remember if you start desktop mode without that screen attached, it will need to be run *again* when you plug it in.

We are however done! Depending on your screen, you may need some colour correction. I personally recommend redshift for this, I set it up to only adjust the bottom panel to 5500k to offset some overly strong blue tones. This is screen-dependent though, hopefully you get a better calibrated screen!

# Emulation
This project was mostly made to use with a certain (now defunct, within an hour of me finishing this project, go figure) lemony emulator for a certain clamshell dual-screen system. The only thing you really need to configure in that, is to enable the separate windows layout, and move the bottom screen to the external panel and the top to the internal. You can switch on fullscreen to make the top screen fullscreen, but this won't affect the window for the bottom screen.

To remedy this, we can use KDE's window rules! Right click the title bar for the second screen window, select "More Actions", and then "Configure Special Window Settings..."

Add a title match, and add screen and fullscreen rules both set to force in order to force that window to always show up on the external panel (usually 1) and always fullscreen, as so:

![kde_window_rules.png](/wiki/dual-screen-project/kde_window_rules.png)

This should result in both windows being fullscreen! You may also want to enable "Hide mouse on inactivity" in the lemony emulator's settings, and any graphical enhancements (I personally run at 3x resolution) you wish. This should be all there is to it! I haven't tried this with CEMU but provided it separates the windows, it should be roughly the same.

# Closing Thoughts
This was a really fun project to sink my teeth into. I have since played a full game with this, and enjoyed it immensely. It was fun figuring out FPV drone cables, and I adore the modularity of this whole system. Yes, it's heavier, but - so? I can remove it when I don't need it! I hope this was easy to follow, and if you do follow this project to make this yourself, I'd love to see it!

If you'd like to find me elsewhere, you can find me on the Fediverse on my self-hosted instance at https://hollypop.xyz/holly - I talk about a lot of weird tech projects I dive into, but be warned that it is still a personal account, and I talk a lot about a lot more than *just* tech! 

I'd also like to thank a few friends for their help figuring out the software issues - namely, Ada, RedCyberPandaz, and Syphist. My knowledge of Linux is limited (I like to bend the will of Windows to my own) and they were a huge help getting the alignment sorted out.
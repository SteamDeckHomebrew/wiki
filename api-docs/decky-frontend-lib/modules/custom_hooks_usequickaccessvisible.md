[decky-frontend-lib](../README.md) / [Modules](../modules.md) / custom-hooks/usequickaccessvisible

# Module: custom-hooks/usequickaccessvisible

## Table of contents

### Functions

- [useQuickAccessVisible](custom_hooks_usequickaccessvisible.md#usequickaccessvisible)

## Functions

### useQuickAccessVisible

▸ **useQuickAccessVisible**(): `boolean`

Returns state indicating the visibility of quick access menu.

**`Remarks`**

During development it is possible to open the quick access menu without giving it
focus in some cases. In such cases, the quick access menu state is invisible.

This seems to be impossible to replicate when running the deck normally. Even in
the edge cases it always seems to have a focus.

**`Example`**

```ts
import { VFC, useEffect } from "react";
import { useQuickAccessVisible } from "decky-frontend-lib";

export const PluginPanelView: VFC<{}> = ({ }) => {
  const isVisible = useQuickAccessVisible();

  useEffect(() => {
    if (!isVisible) {
      return;
    }

    const interval = setInterval(() => console.log("Hello world!"), 1000);
    return () => {
      clearInterval(interval);
    }
  }, [isVisible])

  return (
    <div>
      {isVisible ? "VISIBLE" : "INVISIBLE"}
    </div>
  );
};
```

#### Returns

`boolean`

`true` if quick access menu is visible (focused) and `false` otherwise.

#### Defined in

[src/custom-hooks/usequickaccessvisible.tsx:44](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/0ce1b54/src/custom-hooks/usequickaccessvisible.tsx#L44)

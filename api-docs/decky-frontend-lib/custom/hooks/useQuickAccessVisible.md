# custom-hooks/useQuickAccessVisible

## Index

### Functions

- useQuickAccessVisible

## Functions

### useQuickAccessVisible()

Returns state indicating the visibility of quick access menu.

#### Example

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

#### Signature

```ts
useQuickAccessVisible(): boolean;
```

#### Returns

`boolean`

`true` if quick access menu is visible and `false` otherwise.

Defined in:  [src/custom-hooks/useQuickAccessVisible.tsx:39](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/custom-hooks/useQuickAccessVisible.tsx#L39)

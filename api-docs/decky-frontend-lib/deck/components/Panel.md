# deck-components/Panel

## Index

### Interfaces

- PanelSectionProps
- PanelSectionRowProps

### Variables

- PanelSectionRow

### Functions

- Panel
- PanelSection

## Interfaces

### PanelSectionProps

#### Index

##### Properties

- children
- spinner
- title

#### Properties

##### children?

> `ReactNode`

Defined in:  [src/deck-components/Panel.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Panel.tsx#L13)

##### spinner?

> `boolean`

Defined in:  [src/deck-components/Panel.tsx:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Panel.tsx#L12)

##### title?

> `string`

Defined in:  [src/deck-components/Panel.tsx:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Panel.tsx#L11)

---

### PanelSectionRowProps

#### Index

##### Properties

- children

#### Properties

##### children?

> `ReactNode`

Defined in:  [src/deck-components/Panel.tsx:28](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Panel.tsx#L28)

## Variables

### PanelSectionRow

> **`Const`** `any`

Defined in:  [src/deck-components/Panel.tsx:31](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Panel.tsx#L31)

## Functions

### Panel()

#### Signature

```ts
Panel(props: PropsWithChildren<{
    children?: ReactNode;
}>, context?: any): null | ReactElement<any, any>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<{     `children`?: `ReactNode`; }\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### PanelSection()

#### Signature

```ts
PanelSection(props: PropsWithChildren<PanelSectionProps>, context?: any): null | ReactElement<any, any>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[`PanelSectionProps`](Panel#panelsectionprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

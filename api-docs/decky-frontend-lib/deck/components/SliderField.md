# deck-components/SliderField

## Index

### Interfaces

- NotchLabel
- SliderFieldProps

### Functions

- SliderField

## Interfaces

### NotchLabel

#### Index

##### Properties

- label
- notchIndex
- value

#### Properties

##### label

> `string`

Defined in:  [src/deck-components/SliderField.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L8)

##### notchIndex

> `number`

Defined in:  [src/deck-components/SliderField.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L7)

##### value?

> `number`

Defined in:  [src/deck-components/SliderField.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L9)

---

### SliderFieldProps

#### Hierarchy

- [`ItemProps`](Item#itemprops).**SliderFieldProps**

#### Index

##### Properties

- bottomSeparator
- description
- disabled
- editableValue
- icon
- indentLevel
- label
- layout
- max
- min
- minimumDpadGranularity
- notchCount
- notchLabels
- notchTicksVisible
- resetValue
- showValue
- step
- tooltip
- validValues
- value
- valueSuffix

##### Methods

- onChange

#### Properties

##### bottomSeparator?

> `"standard"` \| `"thick"` \| `"none"`

Inherited from: [ItemProps](Item#itemprops).[bottomSeparator](Item#bottomseparator)

Defined in:  [src/deck-components/Item.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L8)

##### description?

> `ReactNode`

Inherited from: [ItemProps](Item#itemprops).[description](Item#description)

Defined in:  [src/deck-components/Item.tsx:5](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L5)

##### disabled?

> `boolean`

Defined in:  [src/deck-components/SliderField.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L22)

##### editableValue?

> `boolean`

Defined in:  [src/deck-components/SliderField.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L23)

##### icon?

> `ReactNode`

Inherited from: [ItemProps](Item#itemprops).[icon](Item#icon)

Defined in:  [src/deck-components/Item.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L7)

##### indentLevel?

> `number`

Inherited from: [ItemProps](Item#itemprops).[indentLevel](Item#indentlevel)

Defined in:  [src/deck-components/Item.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L9)

##### label?

> `ReactNode`

Inherited from: [ItemProps](Item#itemprops).[label](Item#label)

Defined in:  [src/deck-components/Item.tsx:4](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L4)

##### layout?

> `"below"` \| `"inline"`

Inherited from: [ItemProps](Item#itemprops).[layout](Item#layout)

Defined in:  [src/deck-components/Item.tsx:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L6)

##### max?

> `number`

Defined in:  [src/deck-components/SliderField.tsx:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L15)

##### min?

> `number`

Defined in:  [src/deck-components/SliderField.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L14)

##### minimumDpadGranularity?

> `number`

Defined in:  [src/deck-components/SliderField.tsx:26](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L26)

##### notchCount?

> `number`

Defined in:  [src/deck-components/SliderField.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L17)

##### notchLabels?

> [`NotchLabel`](SliderField#notchlabel)[]

Defined in:  [src/deck-components/SliderField.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L18)

##### notchTicksVisible?

> `boolean`

Defined in:  [src/deck-components/SliderField.tsx:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L19)

##### resetValue?

> `number`

Defined in:  [src/deck-components/SliderField.tsx:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L21)

##### showValue?

> `boolean`

Defined in:  [src/deck-components/SliderField.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L20)

##### step?

> `number`

Defined in:  [src/deck-components/SliderField.tsx:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L16)

##### tooltip?

> `string`

Inherited from: [ItemProps](Item#itemprops).[tooltip](Item#tooltip)

Defined in:  [src/deck-components/Item.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L10)

##### validValues?

> `"steps"` \| `"range"` \| (`value`: `number`) => `boolean`

Defined in:  [src/deck-components/SliderField.tsx:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L24)

##### value

> `number`

Defined in:  [src/deck-components/SliderField.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L13)

##### valueSuffix?

> `string`

Defined in:  [src/deck-components/SliderField.tsx:25](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L25)

#### Methods

##### onChange()?

###### Signature

```ts
Optional onChange(value: number): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

###### Returns

`void`

Defined in:  [src/deck-components/SliderField.tsx:27](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L27)

## Functions

### SliderField()

#### Signature

```ts
SliderField(props: PropsWithChildren<SliderFieldProps>, context?: any): null | ReactElement<any, any>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[`SliderFieldProps`](SliderField#sliderfieldprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

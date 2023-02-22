# custom-components/ReorderableList

## Index

### Type Aliases

- ReorderableEntry
- ReorderableListEntryProps
- ReorderableListProps

### Functions

- ReorderableList

## Type Aliases

### ReorderableEntry

> \<`T`\> `object`

```ts
{
    data?: T;
    label: string;
    position: number;
}
```

A ReorderableList entry of type <T>.

#### Param

The name of this entry in the list.

#### Param

Optional data to connect to this entry.

#### Param

The position of this entry in the list.

#### Type parameters

- `T`

#### Type declaration

| Member | Type |
| :------ | :------ |
| `data`? | `T` |
| `label` | `string` |
| `position` | `number` |

Defined in:  [src/custom-components/ReorderableList.tsx:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/custom-components/ReorderableList.tsx#L11)

---

### ReorderableListEntryProps

> \<`T`\> `object`

```ts
{
    animate: boolean;
    children: ReactElement | null;
    entryData: ReorderableEntry<T>;
    fieldProps?: FieldProps;
    listData: ReorderableEntry<T>[];
    reorderEnabled: boolean;
    reorderEntryFunc: CallableFunction;
}
```

Properties for a ReorderableItem component of type <T>

#### Type parameters

- `T`

#### Type declaration

| Member | Type |
| :------ | :------ |
| `animate` | `boolean` |
| `children` | `ReactElement` \| `null` |
| `entryData` | [`ReorderableEntry`](ReorderableList#reorderableentry)\<`T`\> |
| `fieldProps`? | [`FieldProps`](Field#fieldprops) |
| `listData` | [`ReorderableEntry`](ReorderableList#reorderableentry)\<`T`\>[] |
| `reorderEnabled` | `boolean` |
| `reorderEntryFunc` | `CallableFunction` |

Defined in:  [src/custom-components/ReorderableList.tsx:95](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/custom-components/ReorderableList.tsx#L95)

---

### ReorderableListProps

> \<`T`\> `object`

```ts
{
    animate?: boolean;
    entries: ReorderableEntry<T>[];
    fieldProps?: FieldProps;
    interactables?: JSXElementConstructor<{
        entry: ReorderableEntry<T>;
    }>;
    onSave: (entries: ReorderableEntry<T>[]) => void;
}
```

Properties for a ReorderableList component of type <T>.

#### Param

If the list should animate.

#### Default

true

#### Type parameters

- `T`

#### Type declaration

| Member | Type |
| :------ | :------ |
| `animate`? | `boolean` |
| `entries` | [`ReorderableEntry`](ReorderableList#reorderableentry)\<`T`\>[] |
| `fieldProps`? | [`FieldProps`](Field#fieldprops) |
| `interactables`? | `JSXElementConstructor`\<{     `entry`: [`ReorderableEntry`](ReorderableList#reorderableentry)\<`T`\>; }\> |
| `onSave` | (`entries`: [`ReorderableEntry`](ReorderableList#reorderableentry)\<`T`\>[]) => `void` |

Defined in:  [src/custom-components/ReorderableList.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/custom-components/ReorderableList.tsx#L22)

## Functions

### ReorderableList()

A component for creating reorderable lists.

See an example implementation [here](https://github.com/Tormak9970/Component-Testing-Plugin/blob/main/src/testing-window/ReorderableListTest.tsx).

#### Signature

```ts
ReorderableList<T>(props: ReorderableListProps<T>): Element;
```

#### Type parameters

- `T`

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`ReorderableListProps`](ReorderableList#reorderablelistprops)\<`T`\> |

#### Returns

`Element`

Defined in:  [src/custom-components/ReorderableList.tsx:35](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/custom-components/ReorderableList.tsx#L35)

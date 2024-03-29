# deck-hooks/useParams

## Index

### Functions

- useParams

## Functions

### useParams()

Get the current params from ReactRouter

#### Example

```ts
import { useParams } from "decky-frontend-lib";

const { appid } = useParams<{ appid: string }>()
```

#### Signature

```ts
useParams<T>(): T;
```

#### Type parameters

- `T`

#### Returns

`T`

an object with the current ReactRouter params

Defined in:  [src/deck-hooks/useParams.ts:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-hooks/useParams.ts#L13)

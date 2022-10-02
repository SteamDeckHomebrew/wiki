[decky-frontend-lib](../README.md) / [Modules](../modules.md) / webpack

# Module: webpack

## Table of contents

### Modules

- [&lt;internal\&gt;](webpack._internal_.md)

### Type Aliases

- [Module](webpack.md#module)

### Variables

- [CommonUIModule](webpack.md#commonuimodule)
- [IconsModule](webpack.md#iconsmodule)
- [ReactRouter](webpack.md#reactrouter)
- [allModules](webpack.md#allmodules)
- [webpackCache](webpack.md#webpackcache)

### Functions

- [findAllModules](webpack.md#findallmodules)
- [findModule](webpack.md#findmodule)
- [findModuleChild](webpack.md#findmodulechild)

## Type Aliases

### Module

Ƭ **Module**: `any`

#### Defined in

[src/webpack.ts:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/webpack.ts#L9)

## Variables

### CommonUIModule

• `Const` **CommonUIModule**: `any`

#### Defined in

[src/webpack.ts:73](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/webpack.ts#L73)

___

### IconsModule

• `Const` **IconsModule**: `any`

#### Defined in

[src/webpack.ts:81](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/webpack.ts#L81)

___

### ReactRouter

• `Const` **ReactRouter**: `any`

#### Defined in

[src/webpack.ts:89](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/webpack.ts#L89)

___

### allModules

• `Const` **allModules**: [`Module`](webpack.md#module)[]

#### Defined in

[src/webpack.ts:38](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/webpack.ts#L38)

___

### webpackCache

• **webpackCache**: `any` = `{}`

#### Defined in

[src/webpack.ts:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/webpack.ts#L13)

## Functions

### findAllModules

▸ **findAllModules**(`filter`): `any`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `filter` | [`FilterFn`](webpack._internal_.md#filterfn) |

#### Returns

`any`[]

#### Defined in

[src/webpack.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/webpack.ts#L62)

___

### findModule

▸ **findModule**(`filter`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `filter` | [`FilterFn`](webpack._internal_.md#filterfn) |

#### Returns

`any`

#### Defined in

[src/webpack.ts:42](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/webpack.ts#L42)

___

### findModuleChild

▸ **findModuleChild**(`filter`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `filter` | [`FindFn`](webpack._internal_.md#findfn) |

#### Returns

`any`

#### Defined in

[src/webpack.ts:49](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/webpack.ts#L49)

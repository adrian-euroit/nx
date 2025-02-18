# ngrx

Add an ngrx config to a project

## Usage

```bash
nx generate ngrx ...

```

## Options

### directory

Default: `+state`

Type: `string`

The name of the folder used to contain/group the generated NgRx files.

### facade

Default: `false`

Type: `boolean`

Create a Facade class for the the Feature.

### minimal

Default: `false`

Type: `boolean`

Only register the root state management setup or feature state.

### module

Type: `string`

The path to NgModule where the feature state will be registered. The host directory will create/use the new state directory.

### name

Type: `string`

Name of the NgRx feature state, such as "products" or "users"). Recommended to use the plural form of the name.

### onlyAddFiles

Default: `false`

Type: `boolean`

**Deprecated**, use `skipImport`. Only add new NgRx files, without changing the module file (e.g., --onlyAddFiles).

### onlyEmptyRoot

Default: `false`

Type: `boolean`

**Deprecated**, use `minimal`. Do not generate any files. Only generate StoreModule.forRoot and EffectsModule.forRoot (e.g., --onlyEmptyRoot).

### root

Default: `false`

Type: `boolean`

Setup root or feature state management with NgRx.

### skipFormat

Default: `false`

Type: `boolean`

Skip formatting of generated files.

### skipImport

Default: `false`

Type: `boolean`

Generate NgRx feature files without registering the feature in the NgModule.

### skipPackageJson

Default: `false`

Type: `boolean`

Do not update the package.json with NgRx dependencies.

### syntax

Default: `classes`

Type: `string`

Specifies whether to use class-based or creator functions for actions, reducers, and effects.

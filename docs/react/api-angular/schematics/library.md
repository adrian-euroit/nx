# library

Create an Angular library

## Usage

```bash
nx generate library ...

```

## Options

### directory

Type: `string`

A directory where the app is placed

### lazy

Default: `false`

Type: `boolean`

Add RouterModule.forChild when set to true, and a simple array of routes when set to false.

### name

Type: `string`

Library name

### parentModule

Type: `string`

Update the router configuration of the parent module using loadChildren or children, depending on what `lazy` is set to.

### prefix

Alias(es): p

Type: `string`

The prefix to apply to generated selectors.

### publishable

Default: `false`

Type: `boolean`

Generate a simple TS library when set to true.

### routing

Default: `false`

Type: `boolean`

Add router configuration. See lazy for more information.

### simpleModuleName

Default: `false`

Type: `boolean`

Keep the module name simple (when using --directory)

### skipFormat

Default: `false`

Type: `boolean`

Skip formatting files

### skipPackageJson

Default: `false`

Type: `boolean`

Do not add dependencies to package.json.

### skipTsConfig

Default: `false`

Type: `boolean`

Do not update tsconfig.json for development experience.

### style

Default: `css`

Type: `string`

The file extension to be used for style files.

### tags

Type: `string`

Add tags to the library (used for linting)

### unitTestRunner

Default: `jest`

Type: `string`

Test runner to use for unit tests

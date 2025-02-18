# application

Create an Angular application

## Usage

```bash
nx generate application ...

```

## Options

### directory

Type: `string`

The directory of the new application.

### e2eTestRunner

Default: `cypress`

Type: `string`

Test runner to use for end to end (e2e) tests

### enableIvy

Default: `false`

Type: `boolean`

**EXPERIMENTAL** True to create a new app that uses the Ivy rendering engine.

### inlineStyle

Alias(es): s

Default: `false`

Type: `boolean`

Specifies if the style will be in the ts file.

### inlineTemplate

Alias(es): t

Default: `false`

Type: `boolean`

Specifies if the template will be in the ts file.

### linter

Default: `tslint`

Type: `string`

The tool to use for running lint checks.

### name

Type: `string`

The name of the application.

### prefix

Alias(es): p

Type: `string`

The prefix to apply to generated selectors.

### routing

Default: `false`

Type: `boolean`

Generates a routing module.

### skipFormat

Default: `false`

Type: `boolean`

Skip formatting files

### skipPackageJson

Default: `false`

Type: `boolean`

Do not add dependencies to package.json.

### skipTests

Alias(es): S

Default: `false`

Type: `boolean`

Skip creating spec files.

### style

Default: `css`

Type: `string`

The file extension to be used for style files.

### tags

Type: `string`

Add tags to the application (used for linting)

### unitTestRunner

Default: `jest`

Type: `string`

Test runner to use for unit tests

### viewEncapsulation

Type: `string`

Specifies the view encapsulation strategy.

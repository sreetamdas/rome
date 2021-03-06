# `check.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/core/server/commands/check.test.ts --update-snapshots` to update.

## `smoke`

### `console`

```

 project/index.js:1 lint/js/undeclaredVariables ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The unknownVariable variable is undeclared

    unknownVariable
    ^^^^^^^^^^^^^^^

 project/index.js lint/pendingFixes  FIXABLE  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Pending formatting and safe fixes

    1   │ - unknownVariable
      1 │ + unknownVariable;
      2 │ +

  ℹ To apply fixes and formatting run
  $ rome check index.js --apply

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

ℹ Fixes available. To apply safe fixes and formatting run
$ rome check --apply
ℹ To choose fix suggestions run
$ rome check --review
✖ Found 2 problems

```

### `files`

```
# .config/rome.json
{
	"files": {
		"vendorPath": "../remote"
	}
}


# index.js
unknownVariable

```

## `smoke save`

### `console`

```

 project/index.js:1:4 lint/js/undeclaredVariables ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The unformatted variable is undeclared

  > 1 │ if (unformatted) {
      │     ^^^^^^^^^^^
    2 │   swag;
    3 │ }

 project/index.js:2:1 lint/js/undeclaredVariables ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The swag variable is undeclared

    1 │ if (unformatted) {
  > 2 │   swag;
      │   ^^^^
    3 │ }

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✔ 1 file updated
ℹ You can revert these changes with the rome recover pop command
✖ Found 2 problems

```

### `files`

```
# .config/rome.json
{
	"files": {
		"vendorPath": "../remote"
	}
}


# index.js
if (unformatted) {
	swag;
}


```

# `harness.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/lint/rules/harness.test.ts --update-snapshots` to update.

## `html/preferClosingNonVoid`

### `0`

```

 lint/html/preferClosingNonVoid/reject/1/filename.html:1 lint/html/preferClosingNonVoid  FIXABLE  ━━

  ✖ Non-void HTML elements cannot be self-closing. This is valid when using JSX, but not when
    using HTML.

    <div />
    ^^^^

  ℹ Safe fix

    1   │ - <div·/>
      1 │ + <div>
      2 │ + </div>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```
<div>
</div>

```

### `1`

```
✔ No known problems!

```

### `1: formatted`

```
<div>
</div>

```

### `2`

```
✔ No known problems!

```

### `2: formatted`

```
<div>
	child
</div>

```

### `3`

```
✔ No known problems!

```

### `3: formatted`

```
<input />

```

### `4`

```
✔ No known problems!

```

### `4: formatted`

```
<input />

```

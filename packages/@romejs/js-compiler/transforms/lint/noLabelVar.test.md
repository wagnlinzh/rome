# `noLabelVar.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-compiler/transforms/lint/noLabelVar.test.ts --update-snapshots` to update.

## `format disabled in project config should not regenerate the file`

```
✔ No known problems!

```

## `format enabled in project config should result in regenerated file`

### `0`

```
✔ No known problems!

```

### `0: formatted`

```
foobar('yes');

```

## `no label var`

### `0`

```

 unknown:3:6 lint/noLabelVar ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Labels should not be variable names

    2 │       const x = "test";
  > 3 │       x: const y = "test";
      │       ^^^^^^^^^^^^^^^^^^^^ 
    4 │       

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `1`

```
✔ No known problems!

```

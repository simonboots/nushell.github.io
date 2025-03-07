---
title: dfr all-true
categories: |
  dataframe
version: 0.84.0
dataframe: |
  Returns true if all values are true.
usage: |
  Returns true if all values are true.
---

# <code>{{ $frontmatter.title }}</code> for dataframe

<div class='command-title'>{{ $frontmatter.dataframe }}</div>

## Signature

```> dfr all-true ```


## Input/output types:

| input | output |
| ----- | ------ |
| any   | any    |

## Examples

Returns true if all values are true
```shell
> [true true true] | dfr into-df | dfr all-true
╭───┬──────────╮
│ # │ all_true │
├───┼──────────┤
│ 0 │ true     │
╰───┴──────────╯

```

Checks the result from a comparison
```shell
> let s = ([5 6 2 8] | dfr into-df);
    let res = ($s > 9);
    $res | dfr all-true
╭───┬──────────╮
│ # │ all_true │
├───┼──────────┤
│ 0 │ false    │
╰───┴──────────╯

```


**Tips:** Dataframe commands were not shipped in the official binaries by default, you have to build it with `--features=dataframe` flag
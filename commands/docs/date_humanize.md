---
title: date humanize
categories: |
  date
version: 0.84.0
date: |
  Print a 'humanized' format for the date, relative to now.
usage: |
  Print a 'humanized' format for the date, relative to now.
---

# <code>{{ $frontmatter.title }}</code> for date

<div class='command-title'>{{ $frontmatter.date }}</div>

## Signature

```> date humanize ```


## Input/output types:

| input    | output |
| -------- | ------ |
| datetime | string |
| string   | string |
## Examples

Print a 'humanized' format for the date, relative to now.
```shell
> "2021-10-22 20:00:12 +01:00" | date humanize

```

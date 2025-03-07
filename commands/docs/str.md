---
title: str
categories: |
  strings
version: 0.84.0
strings: |
  Various commands for working with string data.
usage: |
  Various commands for working with string data.
---

# <code>{{ $frontmatter.title }}</code> for strings

<div class='command-title'>{{ $frontmatter.strings }}</div>

## Signature

```> str ```


## Input/output types:

| input   | output |
| ------- | ------ |
| nothing | string |

## Notes
You must use one of the following subcommands. Using this command as-is will only produce this help message.

## Subcommands:

| name                                                                     | type    | usage                                                                                                                               |
| ------------------------------------------------------------------------ | ------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| [`str camel-case`](/commands/docs/str_camel-case.md)                     | Builtin | Convert a string to camelCase.                                                                                                      |
| [`str capitalize`](/commands/docs/str_capitalize.md)                     | Builtin | Capitalize first letter of text.                                                                                                    |
| [`str contains`](/commands/docs/str_contains.md)                         | Builtin | Checks if string input contains a substring.                                                                                        |
| [`str distance`](/commands/docs/str_distance.md)                         | Builtin | Compare two strings and return the edit distance/Levenshtein distance.                                                              |
| [`str downcase`](/commands/docs/str_downcase.md)                         | Builtin | Make text lowercase.                                                                                                                |
| [`str ends-with`](/commands/docs/str_ends-with.md)                       | Builtin | Check if an input ends with a string.                                                                                               |
| [`str expand`](/commands/docs/str_expand.md)                             | Builtin | Generates all possible combinations defined in brace expansion syntax.                                                              |
| [`str index-of`](/commands/docs/str_index-of.md)                         | Builtin | Returns start index of first occurrence of string in input, or -1 if no match.                                                      |
| [`str join`](/commands/docs/str_join.md)                                 | Builtin | Concatenate multiple strings into a single string, with an optional separator between each.                                         |
| [`str kebab-case`](/commands/docs/str_kebab-case.md)                     | Builtin | Convert a string to kebab-case.                                                                                                     |
| [`str length`](/commands/docs/str_length.md)                             | Builtin | Output the length of any strings in the pipeline.                                                                                   |
| [`str pascal-case`](/commands/docs/str_pascal-case.md)                   | Builtin | Convert a string to PascalCase.                                                                                                     |
| [`str replace`](/commands/docs/str_replace.md)                           | Builtin | Find and replace text.                                                                                                              |
| [`str reverse`](/commands/docs/str_reverse.md)                           | Builtin | Reverse every string in the pipeline.                                                                                               |
| [`str screaming-snake-case`](/commands/docs/str_screaming-snake-case.md) | Builtin | Convert a string to SCREAMING_SNAKE_CASE.                                                                                           |
| [`str snake-case`](/commands/docs/str_snake-case.md)                     | Builtin | Convert a string to snake_case.                                                                                                     |
| [`str starts-with`](/commands/docs/str_starts-with.md)                   | Builtin | Check if an input starts with a string.                                                                                             |
| [`str substring`](/commands/docs/str_substring.md)                       | Builtin | Get part of a string. Note that the start is included but the end is excluded, and that the first character of a string is index 0. |
| [`str title-case`](/commands/docs/str_title-case.md)                     | Builtin | Convert a string to Title Case.                                                                                                     |
| [`str trim`](/commands/docs/str_trim.md)                                 | Builtin | Trim whitespace or specific character.                                                                                              |
| [`str upcase`](/commands/docs/str_upcase.md)                             | Builtin | Make text uppercase.                                                                                                                |

**Tips:** Command `str` was not included in the official binaries by default, you have to build it with `--features=extra` flag
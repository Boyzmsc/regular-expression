# Regular Expression

## Purpose
- String Search
- String Replace
- String Extract

<br />

## Create RegExp
~~~js
// Creator
new RegExp('exp', 'option')
new RegExp('[a-z]', 'gi')

// Literal
/exp/option
/[a-z]/gi
~~~

<br />

## Methods
| Method  | Syntax                    | Description                                        |
| -------- | ------------------------- | -------------------------------------------------- |
| test     | `regExp.test(str)`        | Return matches                                     |
| match    | `str.match(regExp)`         | Return an array of matching strings                |
| search   | `str.search(regExp)`        | Return an index of matching strings                |
| replace  | `str.replace(regExp, substitute)`       | Replace matching string and Return replaced string |
| split    | `str.split(regExp)`         | Split matching strings and Return them as arrays   |
| toString | `creator_regExp.toString()` | Return to literal string                           |  

<br />

## Flags
| Flag | Description |
| -- | -- |
| g | Match all characters |
| i | Ignore upper/lower case |
| m | Match multiple lines |

<br />

## Test
https://regexr.com
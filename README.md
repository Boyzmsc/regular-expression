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

## Patterns
| Pattern | Description |
| -- | -- |
| ^ab | Match 'ab' at the beginning of the line |
| ab$ | Match 'ab' at the end of the line |
| . | Match any single character |
| a&verbar;b | Match 'a' or 'b' |
| ab? | Match 'ab' or 'a' |

<br />

| Pattern | Description |
| -- | -- |
| {3} | Match 3 consecutive |
| {3,} | Match 3 or more consecutive |
| {3,5} | Match 3 to 5 consecutive |

<br />

| Pattern | Description |
| -- | -- |
| [abc] | Match 'a' or 'b' or 'c' |
| [a-z] | Match 'a' to 'z' (lower) |
| [A-Z] | Match 'A' to 'Z' (upper) |
| [0-9] | Match 0 to 9 |
| [가-힣] | Match '가' to '힣' |

<br />

| Pattern | Description |
| -- | -- |
| \w | Match '_' or words or numbers |
| \b | Match boundary words |
| \d | Match numbers |
| \s | Match spaces or tabs |

<br />

| Pattern | Description |
| -- | -- |
| (?=) | Lookahead |
| (?<=) | Lookbehind |

<br />

## Test
https://regexr.com
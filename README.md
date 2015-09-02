TLDR.js
=======
Unofficial opinionated TL;DR of JavaScript.

# Index
1. [Intro](#intro)
1. [Strings](#strings)
1. [Loops](#Loops)
1. [Functions](#functions)

# Intro
Intro to JavaScript.

# Strings
## Single or Double quotes?
It doesn't matter... as long as you use single quotes.

## slice, substr, and substring
+ `slice` Use it if you know the start and the end.
+ `substr` Use it if you know the start and the length.
+ `substring` Don't use it because it's just a dumb version of `slice`.

# Loops
## Statements
### Conditional
+ `for` Use it when you know the start and end of a loop.
  + `for...in`
  + `for...of`
  + `for each...in` Don't use it because it's obsolete. Use `for...of` instead.
+ `while` Use it when you know the start but not the end of a loop.
  + `do...while`

### Operational
+ *`label`
+ `break`
+ `continue`

## Arrays
+ `forEach`

# Functions

# "Falsey" values
+ Don't use 'undefined' in your code.

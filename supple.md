# Supplementary homework

### String homework
##### substring (5 pts)
Write a function `substring` that takes 2 strings returning a boolean indicating whether the first is a substring of the other. A substring (of a string **S**) is any string that appears as a whole string *in* **S**. In other words, a substring (of a string **S**) is any string, given some (possibly empty) prefix and (possibly empty) suffix, is equal to **S**. e.g.
 - `'abc'` is a substring of `'abcdef'`
 - `'bcd'` is a substring of `'abcdef'`
 - `'def'` is a substring of `'abcdef'`
 - `'cba'` ***isn't*** a substring of `'abcdef'`
 - `'abd'` ***isn't*** a substring of `'abcdef'`
 - `'acf'` ***isn't*** a substring of `'abcdef'`

P.S. - There is a keyword in python that implements this already. It is called `in`. Since it is a keyword, it doesn't use the function syntax, but is instead used as an infix operator. `'abc' in 'dabce'` evaluates to `True`.
**Do not** implement `substring` with `in`. i.e. do not write `def contains(c,s): return c in s`

Hint: This will require a double loop.

##### subsequence (5 pts)
Write a function `subsequence` that takes 2 strings returning a boolean indicating whether the first is a subsequence of the other. A subsequence (of a string **S**) is a string, whose individual characters appear in **S**, in order, but are not necessarily contiguous (not next to each other).

 - `'abd'` is a subsequence of `'abcdef'`
 - `'acf'` is a subsequence of `'abcdef'`
 - `'bcd'` is a subsequence of `'abcdef'`
 - `'acb'` ***isn't*** a subsequence of `'abcdef'`
 - `'cba'` ***isn't*** a subsequence of `'abcdef'`
 - `'dbc'` ***isn't*** a subsequence of `'abcdef'`

### Visual/layout String homework

###### squares (5 pts)
Write a function `squares(n)` that takes a number *n*, and returns a string. When printed, the string should show a square of asterisks, with *n* asterisks per side. Horizontally, asterisks should not be placed next to each other, but instead have a space inbetween everry asterisk.  e.g.

`squares(3)` should (return a string, that when printed out) prints

    * * *
    *   *  
    * * *

`squares(5)` should (return a string, that when printed out) prints

    * * * * *
    *       *
    *       *
    *       *
    * * * * *

P.S. - remember you can concatenate/join/combine strings with the `+` operator. `'Python ' + ' is fun'` evaluates to `'Python is fun'`. And, that `'\n'` is the newline "character" that when printed, introduces a newline. `print('first line\nsecondline')` prints

    first line
    second line

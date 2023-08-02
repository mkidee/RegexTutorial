# Terms Cheat Sheet

If you're new to coding or simply want to be able to review some coding terms, this is the perfect place to start.

## Summary

This is beginner code to be able to have basic examples to increase knowledge as you strive to increase your skill.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)

## Regex Components

Regex components are used to define parrterns for searching and/or manipulating/editing text. These components are the following terms: Anchors, Quantifiers, Grouping Constructs, Bracket Expressions, Chracter Classes, The OR Operator, Flags, Character Escapes, and Author. Here is an example that includes all of these components: --
/^[a-z0-9_-]{4,21}$/ -- This search includes the following: all letters a-z, digits 0-9, and picking between 4 and 21.

### Anchors

Anchors are basic components. They are the beginning and the end of our search code. The "^" meaning the start, and the "$" meaning the end of our code.
    /^[a-z0-9_-]{4,21}$/ (Start^ and End$)

### Quantifiers

Quantifiers indicate how many times a preceding element should repeat itself, for example: \* (zero or more), + (one or more), ? (zero or one), {n}, {n,}, {n,x}, etc.

### OR Operator

The OR Operator is used when you want to check for certain characters (using "|" to indicate an addtional character). For example, if you had the words cat, cut, cod, cet, and cit; and you used the OR Operator as such: " c(u|a|o)t ", then the words 'cut, cat, cot' would return as 'true' and the others would return 'false'.

### Character Classes

Character Classes check for specific sets of characters, even one character in a word that is found in the character class will return a match. Ex: \c (cat), \z (I like zebras), \k (kangaroo dad), etc.

### Flags

Flags are used to indicate how regex will initiate the code search. Ex: 'g' is a global search, 'i' is a insensitive search, and 'm' is a multi-line search.

### Grouping Constructs

The primary way you group a section of a regex is by using parentheses (()). Enclose parts of the pattern in () to group and capture them for later use.

### Bracket Expressions

    Brackets are exactly that '[]'. An expression for a number search such as '[7-13]' is an example of Bracket Expression.

### Character Escapes

    Use '\' when searching for strings that would have special characters that are the same in particular component of the code. Using one open curly brace ({) in regex searches for the charcter itself instead of starging a quantifier.

## Author

    My name is Mckay Memmott, I'm a student at the UofU for full stack development. My github: https://github.com/mkidee

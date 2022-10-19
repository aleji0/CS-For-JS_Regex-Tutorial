# Regex Tutorial

This tutorial was created to help you understand what a regex is. A regex is a string of characters that details a specific search pattern within that string. Characters can be found or found and replaced using this. These are often used to validate input or, in this case, for matching characters in valid e-mail addresses.

## Summary

This tutorial will be defining components of regex, and describing the components of this: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/` for some of the examples. This exmaple is a regular expression for validating an email address. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
The '^' is the anchor that marks the beginning of the expression, the '$' anchor is the end of the expression.
### Quantifiers
Quantifiers indicate how many occurences of a character or group must be present in the input for a match to be found. When used in a regular expression, the characters: '+','?','{'.'}', and '"' are quantifiers. In the regex provided above, the '+' matches the letter, number, or character before it. The '?' means once or none, or can be used to make quantifiers lazy. The braces dicate how many times something should be done. In this exmaple "{2,4}" indicates a range of two to four times.
### Grouping Constructs
Grouping constructs describe the sub-expressions of a regular expression, and capture the sub-strings of an input string.
### Bracket Expressions
The bracket expressions, which use the '[' & ']' square bracket characters, enclose which information is supposed to be matched.
### Character Classes
Character classes distinguish types of characters, such as letters or digits. In this example the '\d' means it searches for digits. A capital '\D' would search for non-digit characters. A '\s' would search for a whitespace character, '\S' for non-whitespace characters, and '\w' matches word characters, and '\W' matches non-word characters.
### The OR Operator
The OR operator is used with the pipe character '|'. This character acts as an OR operator between the characters on either side and can be chained together in a series. It essentially translates to 'this or that'.
### Flags
Flags are used at the end of a regular expression to match patterns more with more specific parameters. This example does not use any flags.
### Character Escapes
The '\' escapes the character following it. '\.' would indicate that it is looking for a '.', and not reading it to mean "any character".
## Author

This tutorial was made by Alex Springer. 

[GitHub:](http://github.com/aleji0)
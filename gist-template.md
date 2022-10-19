# Title (replace with your title)

This tutorial was created to help you understand what a regex is. A regex is a string of characters that details a specific search pattern within that string. Characters can be found or found and replaced using this. These are often used to validate input or, in this case, for matching characters in valid e-mail addresses.

## Summary

This tutorial will be describing the components of this `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/` regular expression for validating an email address. 

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
Grouping constructs describe the sub-expressions of a regular expression and capture the substrings of an input string.
### Bracket Expressions

### Character Classes
Character classes are defined by square brackets '[]'. They are used to match only one of several characters. In this example it is matching one lower case letter or digit.
### The OR Operator
The OR operator (|)
### Flags
Flags are used at the end of a regular expression to match patterns more with more specific parameters. This example does not use and flags.
### Character Escapes
The '\' escapes the character following it. '\.' would indicate that it is looking for a '.', and not reading it to mean "any character".
## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)


[THIS IS A LINK](http://imalink.com)
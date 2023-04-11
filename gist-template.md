# Title (replace with your title)

Introductory paragraph (replace this with your text)

Regular expressions are widely used in computer science and can be helpful in a variety of ways. In this tutorial, I will specifically break down a regular expression and describe what each snippet does.

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

* Matching an Email:  `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`


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
Anchors are the tags that are used to signal the beginning of the code snippet and the end of the snippet. The ^ sign is used in the beginning of the code and the $ sign is used at the end of the code. In the regex we are analyzing, the ^ anchor is preceding the bracket statements and the $ anchor is used after the bracket expressions and quantifers. 

### Quantifiers
Quantifiers are the set of limits that the regex must pass in order for the expression to be valid. 
The * quantifier signals that regex should match the pattern zero or more times.
The + quantifier signals that regex should match the pattern one or more times.
The ? quantifier signals that regex should match the pattern zero or one time.
The code inside curly brackets are also considered quantifiers that limit the regex. In the regex we are analyzing, the quantifiers are after each bracket expression. In the first and second group construct, the quantifier is +. In the last group construct, the quantifier is {2,6}, which means that the construct must be between 2 and 6 characters. 

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)

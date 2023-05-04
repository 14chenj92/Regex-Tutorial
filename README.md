# Regex Tutorial

Regular expressions are widely used in computer science and can be helpful in a variety of ways. It is important to understand the specifics of the code in order to create and input limitations for future projects. 

## Summary

* Matching an Email:  `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

In this tutorial, we will be defining the code based off a regular expression to match an email address. I will specifically break down a regular expression and describe what each snippet does. I will dive into more detail of what each section of this code does in regex components. 


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
Grouping constructs separate the regex into sections using parentheses. In our regex expression, the grouping constructs are divded into 3 sections: one after the ^ anchor, one after the @ symbol, and the last one preceding the $ anchor. The code inside the grouping construct sets the limits for the section of the regex. 

### Bracket Expressions
Bracket expressions are the square brackets that specify the criteria for the regex to match. In the regex we are analyzing, the first bracket expression inside the first construct states that the criteria includes lowercase characters a to z, numbers 0 to 9, an underscore, a period, and a hyphen. In the second bracket expression, the the criteria is the same as the first construct except it is presented with a class /d instead of [0,9]. The last bracket expression only includes lowercase letters from a-z with the limitation of 2 to 6 characters. 

### Character Classes
Character classes define a set of characters that can match in an input string. In our sample regex, some character classes include [a-z] and [0-9]. There are also predefined character classes such as: 
\d-matches any digit character
\w—matches any alphabet letter and digit character, including uppercase/lowercase as well as underscore
\s matches a whitespace character
In our regex expression, /d is used as character class to signal a match to digit character, or [0,9].

### The OR Operator
The OR operator (|) creates a statement that creates an alternative to the criteria that needs to be met for the code. For example, (a|b) would mean that a or b can satsify the requirement for the expression. 

### Flags
Flags provide additional functionality for the regex and are placed at the end of the expression. 
The most common flags are:
g—Global search
i—Case-insensitive search
m—Multi-line search

### Character Escapes
Character Escapes are used as a backslash(/), where it would prevent the code to be interpreted literally. Character escapes are also tied to character classes where the backslash would create a different meaning to the code entirely. An example can be given in our regex expression where d by itself would match the d character, while /d would match any digit character. 

## Author

Written by Jonathan Chen. I am currently a student at the UC Berkeley Extension Full-Stack bootcamp. I am coding on a regular basis in order to improve my skills and break into the tech field. 

Github profile: [github.com/14chenj92](github.com/14chenj92)

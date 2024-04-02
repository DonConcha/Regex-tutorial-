# Regex Email tutorial 

In this tutorial, I will breakdown one of the most commonly used expressions known as "Matching an Email".

## Summary
Matching an Email: 
This breakdown will include the function & the major conecepts that Regex utilises to make sure the string that was given matches the template to verify an email adress. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Boundaries](#boundaries)
- [Back-references](#back-references)

## Regex Components

### Anchors
`^`: Must be needed to start the beginning of the string.
`$`: Must be needed to end the string. 
Both anchors are necessary to complete a full string & make sure the regex matches the email. 

### Quantifiers
`+`: Needed to match one or more elements 
`{2,6}`: Given the range of 2 to 6 characters to be match inside of the brackets.

### OR Operator
|: Allows any alternative matching patters 

### Character Classes
Predefined & special characters that match a single character from a group.

### Grouping and Capturing
`()`: Within the set of  parentheses is taken as a single group & allows the elements to be a single unit. 

### Bracket Expressions
`[]`:Within the brackets, characters inside will be considered in a group.
Combined with a quantifier + all characters will match inside the brackets.

## Author
Ronaldo Faz : https://github.com/DonConcha

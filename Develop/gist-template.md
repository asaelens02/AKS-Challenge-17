# AKS-Challenge 17-REGEX

Regex is an abbreviation for a regular expression. A regular expression is a pattern that describes a certain amount of text. 

## Summary

I will be describing the Regex for "Matching an email" /^[A-Za-z0-9_!#$%&'*+\/=?`{|}~^.-]+@[A-Za-z0-9.-]+$/gm is the regular expression I will be describing. A matching email regex is used to validate an email address when entered into a form or answering a prompt.
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components
    

### Anchors

Anchors, like the name implies, are used to define or hold a position before, after, or within the characters. The dollar sign $ and the carot ^ are the end and beginning of the regular expression. 

### Quantifiers

Quantifiers specify a quantity of instances of a character, group or character class. For an email regex one would want to use a greedy quantifier such as "+" as it will match as many instances as possible. In the email regular expression: /^[A-Za-z0-9_!#$%&'*+\/=?`{|}~^.-]+ the regex will look for at least one of everything in the brackets. Once the regex gets to the @ it will stop searching. 


### OR Operator
Not used for this regex

### Character Classes

defines a set of characters to be matched. 

### Flags

The flag is used to delimit the regular expression. It is used before and after the expression. 

### Grouping and Capturing
In this specific email regex brackets are used to group the pieces of our expression together. The username is grouped  and then the email provider name is grouped. 

### Bracket Expressions

Brackets allow a regex to match characters within a range. So within our email regex it is analyzing [a-z0-9_\.-] and is looking for any letter a-z and any number 0-9. 

### Greedy and Lazy Match
Greedy matches such as + will try to match as many characters as possible whereas a Lazy match will try to match as few characters as possible. 

### Boundaries

A word boundary,  is a position between \w and \W, or at the beginning or end of a string if it begins or ends  with a word character.

### Back-references

### Look-ahead and Look-behind

## Author

Ashley Saelens
https://github.com/asaelens02/AKS-Challenge-17



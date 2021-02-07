# Title (replace with your title)

In this tutorial, I'm going to introduce one of the more commonly used Regular Expressions and, by describing how it works, explain some important regex concepts.

## Summary

We will be walking through the following regex, explaining what each component does.

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

This regex makes sure that the given string matches the template for an email address.

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

The two anchors in regex are ^ and $.

^ means that the following code must appear at the beginning of the string.

$ means that the preceding code must appear at the end of the string.

Because our regular expression contains both, a given string must match all the given specifications exactly, or it won't be a match.

Although this sounds limiting, you will see how quantifiers, grouping and bracket expressions allow a large range of variation in the given string.

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)

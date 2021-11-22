# Regex: What is it?

Regex or regular expressions are a sequence of characters that form a search pattern. They are used to match character combinations in strings. For example; you can test a string for a character to verify that a phone number is valid.
## Summary

The regex code that I will be describing for you here is 
```(\W|^)po[#\-]{0,1}\s{0,1}\d{2}[\s-]{0,1}\d{4}(\W|$)```
This is a regular expression that matches and alphanumeric format, so it can match order numbers for example.

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

Anchors tell the computer when the regex starts and ends so that it knows what sit's looking for
```^``` = tells the computer this is the beginning of the of the expression.
```$``` = tells the computer this is the end of the expression.

### Quantifiers

Quantifies specify for the computer how many instances of a character, group, or class should be present for the expression to find it.
The quantifiers in this expression include = 
```{0,1}``` this means it needs to Match from 0 to 1 times, 
'```{2}``` which means it needs to match exactly 2 times,
'```{4}``` which means it needs to match exactly 4 times

### OR Operator

The OR Operator, also know as the alternation (also not called O.R., it is called or). It is written with ```|```. There is two in this expression one at the beginning and at the end. 

### Character Classes

A character class is a special notation that matches any symbol from the set. The character classes used in this expression are:

```\d``` A digit: a character from 0 to 9. 

```\s```A space symbol: includes spaces, tabs \t, newlines \n and few other rare characters, such as \v, \f and \r.

```\W``` is an inverse class Non-wordly character: anything but \w, e.g a non-latin letter or a space.

### Flags

Flags are tokens that modify the expressions behavior of the search. This expression has no flags but I will include an example.
```i``` is ignore casing, it makes the expression search case-insensitively.

### Grouping and Capturing

Capturing groups is what is used to mark multiple characters into a group or unit. You can use this to apply modifers to them. 
The ones used in this expression are:
```(\W|^)``` and ```(\W|$)```

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)

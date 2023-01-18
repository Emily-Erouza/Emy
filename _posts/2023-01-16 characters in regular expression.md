---
Layout:
Title:  Characters in Regular Expression
date: 2023-01-16
Categories:
---
# Intoduction
- Today i learned about Reguar Expresion
# Body
- 1.Match Single Characters Not Specified.

caret character(^)
- 2.Find Characters with Lazy Matching.

the regex /t[a-z]*i/
This regex is basically a pattern that starts with t, ends with i, and has some letters in between.
- 3.Match Ending String Patterns

the dollar sign character $
You can search the end of strings using the dollar sign character $ at the end of the regex.
- 4.Match All Letters and Numbers.

all letters of the alphabet with [a-z].
The closest character class in JavaScript to match the alphabet is \w. This shortcut is equal to [A-Za-z0-9_]
the underscore character (_).
- 5.Match Whitespace

for whitespace using \s, which is a lowercase s.
This pattern not only matches whitespace, but also carriage return, tab, form feed, and new line characters.
- 6.Positive and Negative Lookahead.

A positive lookahead is used as (?=...) where the ... is the required part that is not matched.
A negative lookahead is used as (?!...) where the ... is the pattern that you do not want to be there.
- 7.Reuse Patterns Using Capture Groups.

Capture groups can be used to find repeated substrings.
e.g : let repeatStr = "row row row your boat";
- 8.Use Capture Groups to Search and Replace

The inputs for .replace() is first the regex pattern you want to search for.
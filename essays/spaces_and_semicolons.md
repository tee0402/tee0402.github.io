---
layout: essay
type: essay
title: Spaces and Semicolons
date: 2017-09-16
labels:
  - Software Engineering
  - Coding Standards
---

<img class="ui large right floated image" src="../images/javascript.png">

I have an obsession with spaces and semicolons in code. I agonize over whether I should leave a space between an "if" and an opening parenthesis. I am adamant about not putting opening curly braces on a new line and "lining them up" because I think that it just does not look good and is not worth the space of a new line.

## What Python Taught Me

Because of my background in other languages, I often mistakenly put a semicolon at the end of a line when coding in Python, only to realize that it delimits lines by spacing instead of semicolons. At first I was angry with Python for not adhering to established coding standards that have been used for decades. But then I realized that maybe the standard was wrong. Maybe it <strong>is</strong> better to delimit statements based on spaces and newlines, which we already do (or should do) in other languages, and make the semicolon obsolete.

## Not Just Aesthetics

By default, Python (and practically all other languages) implements its own coding standard. For example, Python requires that every line in the same block of code must have the same indentation. However, this is not just to make the code look prettier. The lack of curly braces to denote a block of code means that the interpreter cannot understand the code if it does not implement this standard.

## Do Not Be a Coding Standard Nazi

Despite being obsessed with every little detail in my code, I do not think that you should force your coding standard onto others, who might have different preferences for how their code should look. As long as the style does not interfere with the correctness of the program, it should not matter very much whether you put a space after an "if". However, I am not against coding standards embedded in languages themselves, as long as they are well-thought-out (e.g. Python's elimination of semicolons) and not about nitpicking at unimportant details (e.g. 2 spaces vs. 4 spaces in a tab indentation).

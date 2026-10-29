---
title: Simple is better than complex
tags:
- Python
classes: wide
---

This is my take on the controversial topic of duck typing.  Many consider the lack of typed variables in Python as a disadvantage, but I disagree.  In one sense Python is a typed language in that  everything has a type; because there is only one, object.

I agree that for real time processes, where speed is of the essence or something like microcontroller code, where every byte has to be carefully scrutinised, duck typing is wasteful.  But generaly this is not the case and the whole point of objects is that they are self contained, with the internals well hidden.

You see, I think the real advantage of duck typing is that it enables code clarity, in the sense of the naming of symbols. [Readability  counts]({% post_url 2026-07-11-readability-counts %}). It is a real pain to remember, and have to move the editor cursor to add a new type definition line,  just to add a statement needing a  temporary  variable.   Pascal and Delphi were agony in this regard.

I think this is how  and why  obscure code comes about.  Using generic variables or reusing names, conveniently avoids takiing your mind (and cursor) away from the task at hand just to add the type definition statement. 

It also saves most of the complexity associated with definition overrides.  There is no need to define separately named functions to do the  equivalent thing for different types. So def square(value): works for int, float, complex etc. The object, value deals with the type; that after all the whole point of object orientation.

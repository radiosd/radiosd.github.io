---
title: Now is better than never
classes: wide
tags:
- Python
---

I am thinking here of the immediate interactive nature of the Python interpreter.

Many people discount Python as slow because it is uses an interpreter, though this is a somewhat superficial assessment.  It reminds me of the old and patently false arguments against Forth, the Latin of computer languages.  Anyway, behind the scenes, many commonly used libraries link to optimised compiled code, just like other compiled language counterparts.

The 'compiled' byte code is very compact, efficient and easily mapped into highly optimised code on any given machine.  (again quite like Forth) This is one reason that Python is available on so many different platforms.

This is not a bug, it's a feature.   The interpretive nature of Python really comes to the fore during code development.  To me this is the justification of the main-name idiom, allowing one to run the code for a module in a shell while leaving an interactive prompt to test and try out new code.   

I consider this to be the first level of module test.   Add a bunch of assert statements into the main-name code block and that acts as a basic test.  Also in development/debugging, initialise objects as needed, then put some troublesome code there, run it and you can interact directly with the results to figure out what is what  This approach, combined with introspection, is really productive, avoiding the complication of an interactive debugger.

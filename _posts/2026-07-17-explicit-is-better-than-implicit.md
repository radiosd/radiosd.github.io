---
title: Explicit is Better than Implicit
tags:
- Python
classes: wide
---

Another way of saying keep it simple. Someone with no prior knowledge of your program should still
 be able to understand what is happening in your code.  This goes back to my previous post about 
[dot notation]({% post_url 2026-01-24-dot-notation %} ).  So not only should the code be easy to 
understand, and here duck typying is a great help, but being able to track back through the layers 
of definitions is essential.  Really it all comes back to the idea of name space, which is another 
Zen of Python.

Some dispare of the idea of duck typing and the lack of symbol types, but this to me rather misses 
the point.  Python is typed in the sense that there is one (and only one) type and that is object.  
Symbols refer to objects and there internal structure that determins what they do.

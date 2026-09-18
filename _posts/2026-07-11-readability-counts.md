---
title: Readability Counts
layout: single
classes: wide
tags:
- Python
---

This is at the heart of my enthusiasm for Python.  This is not in the sense of the elegant of the 
syntax [Beautiful is Better than Ugly]( {% post_url 2026-08-17-beautiful-is-better-than-ugly %}), 
though that must help. It is a matter of usefulness and saving time. I'm sure I am not alone when 
going back to some of my own code and have to scratch my head to understand it.  Of couse that 
goes double for someone else's code.  But I really find that the ease of defining functions and 
structures, the way modules are imported and the way one approaches coding does help. Then of 
course you only write it once, you (and maybe others) read it many times. So time taken for extra 
typing or clarity is paid back many fold later.  Also, there is no excuse, editors now have code 
completion and other tools that save keystrokes, so why have some obscure *i = <some calculation>* when it could 
be *found_items = <some calculation>*; much clearer.

Another very important idea here is introspection, where defined objects themselves can be examined 
for information.  When defining a new class or function, it is not unusual to add some useful 
comment, then putting in tripple quotes turns into help, that is available from the command line or the 
editor or even a pop up bubble as you type the synbol.  So easy, making readable code more usable 
as well.

Finally, I think the idea that all symbols are explictly named via the 
[dot notation]({% post_url 2026-01-24-dot-notation%}) is brilliant.  When re-reading source code 
there is never any doubt what a symbol refers to and, you can find it either in that file or via 
the file specifically named in an  import statement.

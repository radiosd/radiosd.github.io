---
title: Dot Notation
tags:
- Python
layout: single
classes: wide
---

Python uses the idea of name_space, which explicitly gives all symbols unique names and compound names are delineated by a ‘.’ Hence dot dotation.


This idea is similar to that of scope, in that names are unique to a context level, but goes further in actually embedding the context into the name.  For example, math.pi represents the symbol for pi in the math module and there will have to be an ‘import math’ statement in the source file. This is unlike for example C, where items included from a header file use the symbol from that file. It is impossible to tell from just the source code where pi comes from.


Using name_space results much more readable code and means that all origin (source) of any symbols can be easily identifies.  The converse being the case in C, where the reader of the source code cannot easily tell where a symbol comes from.  It could be a reserved symbol or declared in the source, or included from any one of those file in the source.


Zen “Readability (really) matters”

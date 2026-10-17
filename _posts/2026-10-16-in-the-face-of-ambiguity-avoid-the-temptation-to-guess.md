---
title: In the face of ambiguity, avoid the temptation to guess
tags:
- Python
---

It seems to me that Python incorporates all the best bits of other computer languages.  The ones that deserve highlighting in this context are the various code timing techniques.  They let you compare different coding approaches to a problem and find the optimum solution.

If there is doubt about the most efficient way to code a calculation, just time it and find out. 

For code snippets, use the **timeit** module, either from the command line.
python -m timeit "'-'.join(str(n) for n in range(100))"

or within a program for a specific block
```python
import timeit
start = timeit.timeit()
print("hello")
end = timeit.timeit()
print(end - start)
```

for larger code blocks within a program use the **time** module
```python
import time

start = time.perf_counter()
# include the code to be evaluated
end = time.perf_counter()
print(end - start)
```

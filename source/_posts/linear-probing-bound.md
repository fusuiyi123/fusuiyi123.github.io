---
title: Expected Cost of Linear Probing
date: 2019-01-24 20:50:21
tags:
  - probabilistic algorithms
  - statistics
categories: mathematics
---

Danni is taking [Comp580](https://www.cs.rice.edu/~as143/COMP480_580_Spring19/index.html) at Rice. She is learning to analyze the expected cost of linear probing which is used to handle the collision in hashing. I want to share some interesting results without diving into details.  
**Therom:** With 3-independent hashing we can prove an O(logn) expected costs of look up.  
**Therom:** With 5-independent hashing we can prove an O(1) expected costs of look up.  
The proof are basically propability and statistics, it needs to use Chebyshev’s Inequalities, 4th moment bound and the variable independence derived from the 3/5-indenpendent hashing. If interested, this [stanford lecture note](http://web.stanford.edu/class/archive/cs/cs166/cs166.1166/lectures/12/Small12.pdf) is very useful.

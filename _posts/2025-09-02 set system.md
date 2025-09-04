---
title: Construction of set system
author: Jinye
date: 2025-09-02 00:27:00 -0400
# categories:
#   - Blogging
#   - Tutorial
tags: [PIR][MVF]
pin: false
math: true
render_with_liquid: false
---

Today, we will discuss the Grolmusz construction of set systems, which provides the best-known construction of matching vector families. We will first revisit the roadmap that connects set systems to matching vector families, then to matching vector codes, and finally to private information retrieval. After that, we will show the construction of the set system. To be specific, we will show for every integer $n,m>0$ and $m=p_1^{t_1}\cdots p_r^{t_r}$ where $p_i$ are distinct primes. There exists a set system $\mathcal{H}$ over a universe $2(m-1)n^{2d}/d!$ elements where $d=O(n^{1/r})$ satisfying that the cardinality of each set in $\mathcal{H}$ equals to $0$ modulo $m$, the intersection of every two distinct sets is not $0$ modulo $m$, and the size of $\mathcal{H}$ is $n^n$. The construction is based on the previous result that low low-degree weakly representable polynomial of $OR$ exists. 

**Open questions**

1. For a fixed universe, can we construct a larger set system? Or based on this set-system construction, is it possible to obtain a better matching vector family?
1. Can we propose a lower bound of the size of such a set system?


**Reference** 

- Grolmusz construction: https://link.springer.com/content/pdf/10.1007/s004930070032.pdf
- More information about matching vector family and matching vector code: https://people.csail.mit.edu/dmoshkov/courses/codes/LDC_now.pdf

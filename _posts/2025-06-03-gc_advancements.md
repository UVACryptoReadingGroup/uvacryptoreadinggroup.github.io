---
title: Foundations and Advancements in Garbling Schemes
author: Chase
date: 2025-06-03 00:27:00 -0400
# categories:
#   - Blogging
#   - Tutorial
tags: [GC]
pin: false
math: true
render_with_liquid: false
---

Abstract: Since its inception in the 1980s, Yao’s garbled circuit protocol has served as a fundamental tool for secure multi-party computation, inspiring numerous improvements that reduce the bottleneck of communication. This talk will briefly review the core ideas behind garbling schemes and key optimizations over the years, before discussing recent advancements that expand the scope of garbling, allowing larger, more expressive gates to be incorporated into garbling schemes. The goal is to provide a clear and accessible overview of the historical development and current state of garbling schemes, highlighting how modern techniques address the central challenge of communication overhead by moving beyond traditional AND/XOR representations.

Open Questions:
Are there other types of larger gates that can be efficiently garbled without decomposing down to basic gates?
Can the state-of-the-art 3/2 ciphertexts for AND gates be beaten while preserving FreeXOR?

Papers Referenced:
Yao’s Garbled Circuits: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4568207 
Point-and-Permute: https://dl.acm.org/doi/pdf/10.1145/100216.100287 
Row Reduction: https://dl.acm.org/doi/pdf/10.1145/336992.337028 
FreeXOR: https://www.cs.toronto.edu/~vlad/papers/XOR_ICALP08.pdf 
Half Gates: https://eprint.iacr.org/2014/756.pdf 
Three Half Gates: https://eprint.iacr.org/2021/749.pdf 
One-Hot Garbling: https://eprint.iacr.org/2022/798.pdf 
Garbled Lookup Tables: https://eprint.iacr.org/2024/369.pdf 

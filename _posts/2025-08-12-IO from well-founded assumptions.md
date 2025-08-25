---
title: Indistinguishability Obfuscation from well-founded Assumption
author: Jinye
date: 2025-08-12 00:27:00 -0400
# categories:
#   - Blogging
#   - Tutorial
tags: [IO]
pin: false
math: true
render_with_liquid: false
---

Today, we will discuss the construction of indistinguishability obfuscation (iO) based on well-founded assumptions. This construction was proposed by Jain, Lin, and Sahai in 2020. Their main result shows that iO can be realized under the assumptions of SXDH, LWE, LPN, and the existence of a Boolean PRG in $NC^0$ with polynomial stretch. The key contribution in this work is that they construct a Structured Seed PRG (sPRG) that is computable by a degree-2 computation in the private seed, based on the assumptions of LPN and the existence of a Boolean PRG in $NC^0$. The idea is to encrypt the seed of the PRG using the LPN assumption and make the encrypted seed a part of the public seed. The private seed is just used to correct the difference and make the output of sPRG the same as the PRG with the same seed.

**Open questions**

1. What's the minimal assumption that implies IO? Is it possible to construct IO only on lattice-based assumptions?
1. Can we construct more efficient IO?


**Reference** 

- [JLS21] https://eprint.iacr.org/2020/1003.pdf

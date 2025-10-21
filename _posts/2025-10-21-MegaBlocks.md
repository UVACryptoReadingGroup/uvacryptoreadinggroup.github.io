---
title: 'MegaBlocks: Breaking the Logarithmic I/O-Overhead Barrier for Oblivious RAM'
author: Wei-Kai
date: 2025-10-21 00:27:00 -0400
# categories:
#   - Blogging
#   - Tutorial
tags: [ORAM]
pin: false
math: true
render_with_liquid: false
---

How to securely delegate storage to an untrusted server? The access pattern to the storage often divulges sensitive information about the data, even when the data is securely encrypted. Oblivious RAM (ORAM) is a compiler that generically transforms any access pattern to unintelligible but functionally equivalent ones. When Goldreich introduced ORAM in 1987, a lower bound of Ω(log n) for ORAMs was also proved. In this talk, we circumvent the logarithmic lower bound in a natural asymmetric setting, where the block size of the storage is larger than the word size simulated by ORAM. We provide both a lower bound and an optimal ORAM scheme in the asymmetric setting. Our scheme is implemented and open-sourced, and it outperforms the best-known ORAMs in real-world settings.

This is a joint work with Gilad Asharov, Eliran Eiluz, and Ilan Komargodski.

- Paper, MegaBlocks: [https://eprint.iacr.org/2025/1592.pdf](https://eprint.iacr.org/2025/1592.pdf)
- Paper, lower bound: [https://eprint.iacr.org/2020/1132.pdf](https://eprint.iacr.org/2020/1132.pdf)

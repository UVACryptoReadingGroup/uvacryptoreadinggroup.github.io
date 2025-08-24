---
title: Simulating Time With Square-Root Space
author: Wei-Kai
date: 2025-08-24 00:27:00 -0400
# categories:
#   - Blogging
#   - Tutorial
tags: [Complexity]
pin: false
math: true
render_with_liquid: false
---

Wei-Kai will give an advertisement for the amazing work, *Simulating Time With Square-Root Space*, by Ryan Williams.
The STOC 2025 Best Paper Award also recognizes the result.
Although the result is in complexity, the technique relies on a novel and cool space-efficient algorithm.
Some crypto people are also excited about whether the algorithm could be helpful in crypto.

This paper considers the space complexity of any function that is computable in time $$t$$.
It proves that for any $$t = t(n) \ge n$$, for any function that is computable in time $$t$$ on a multiple-tape Turing machine, the function can be computed in space $$O(\sqrt{t \log t})$$, where $$n$$ is the input size.
The simulation marks a breakthrough, improving the result of Hopcroft, Paul, and Valiant, which was $$O(t/ \log t)$$ space, from 50 years ago [FOCS 1975, JACM 1977].
An important implication is on the problem P versus PSPACE because this result proved that there exist problems solvable in $O(n)$ space but require $$O(n^{2-\epsilon})$$ time.

In addition to the complexity and algorithm concepts, Prof. Williams also reflected on the "fortunate" discovery.
It is a huge encouragement to our theory community.
The original paper and video recording are highly recommended to everyone, with the promise that the video requires only undergraduate-level knowledge.

- Paper: [https://arxiv.org/pdf/2502.17779](https://arxiv.org/pdf/2502.17779)
- Video (IAS): [https://youtu.be/1qwDO5ulUFs?si=wyLf8-XQKSOMPZuo](https://youtu.be/1qwDO5ulUFs?si=wyLf8-XQKSOMPZuo)
- Video (TCS+): [https://youtu.be/tM9ekW6FAS8?si=tvcZHPexYpZ0vjVR](https://youtu.be/tM9ekW6FAS8?si=tvcZHPexYpZ0vjVR)

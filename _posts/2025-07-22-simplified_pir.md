---
title: Simplified PIR
author: Wei-Kai
date: 2025-07-22 00:27:00 -0400
# categories:
#   - Blogging
#   - Tutorial
tags: [PIR]
pin: true
math: true
render_with_liquid: false
---

Private Information Retrieval (PIR) is a useful primitive, practically and theoretically. However, information-theoretic PIRs has been challenging to obtain. In the 2-server setting, the best known result is proposed by Dvir and Gopi in 2014, which is a decade old currently. Moreover, the PIR of Dvir-Gopi is involved. This week, I am reading a recent paper by Alon, Beimal, and Lasri [ABL24], which gives a simplified PIR and achieves the same efficiency as Dvir-Gopi.

- [ABL24] [Simplified PIR and CDS Protocols and Improved Linear Secret-Sharing Schemes.](https://eprint.iacr.org/2024/1599) Bar Alon, Amos Beimel, Or Lasri. eprint 2024.

Resultwise, [ABL24] achieved $$2^{O(\sqrt{\log N \log \log N})}$$ communication for a database of $$N$$ bits, same as Dvir-Gopi asymptotically. Technique-wise, both results black-box use the best known matching vector family, but [ABL24] is simpler in the sense it uses only modular arithmetic. In contrast, Dvir-Gopi went through derivatives and interpolations on polynomials in finite fields. This paper also proposed a framework that captures k-server PIRs for k > 2. Also, a new concept of share conversion is proposed as a building block in the framework.

The main open problem is still improving the communication. Even shaving $$\log \log N$$ factors on the exponent is good and might need new technique or better matching vectors.

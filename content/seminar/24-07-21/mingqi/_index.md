---
title: Equivalence and Similarity Refutation for Probabilistic Programs
date: 2024-07-21
---

**Presenter**: {{% mention "Mingqi Yang" %}}

**Authors**: Krishnendu Chatterjee, Ehsan Kafshdar Goharshady, Petr Novotný and Đorđe Žikelić

**Abstract**: We consider the problems of statically refuting equivalence and similarity of output distributions defined by a pair of probabilistic programs. Equivalence and similarity are two fundamental relational properties of probabilistic programs that are essential for their correctness both in implementation and in compilation. In this work, we present a new method for static equivalence and similarity refutation. Our method refutes equivalence and similarity by computing a function over program outputs whose expected value with respect to the output distributions of two programs is different. The function is computed simultaneously with an upper expectation supermartingale and a lower expectation submartingale for the two programs, which we show to together provide a formal certificate for refuting equivalence and similarity. To the best of our knowledge, our method is the first approach to relational program analysis to offer the combination of the following desirable features: (1) it is fully automated, (2) it is applicable to infinite-state probabilistic programs, and (3) it provides formal guarantees on the correctness of its results. We implement a prototype of our method and our experiments demonstrate the effectiveness of our method to refute equivalence and similarity for a number of examples collected from the literature.

**URL**: https://dl.acm.org/doi/10.1145/3656462

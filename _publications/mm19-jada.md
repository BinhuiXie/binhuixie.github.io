---
title: "Joint Adversarial Domain Adaptation"
collection: publications
permalink: /publications/mm19-jada
date: 2019-10-25
venue: "ACM International Conference on Multimedia 2019"
citation: "Shuang Li, Chi Harold Liu, Binhui Xie, Limin Su, Zhengming Ding, and Gao Huang. Joint adversarial domain adaptation. In ACM MM, pages 729–737. ACM, 2019."
---

[[Paper]](https://dl.acm.org/doi/10.1145/3343031.3351070) [[code]](https://github.com/BIT-DA/JADA)

## Abstract

Domain adaptation aims to transfer the enriched label knowledge from large amounts of source data to unlabeled target data. It has raised significant interest in multimedia analysis. Existing researches mainly focus on learning domain-wise transferable representations via statistical moment matching or adversarial adaptation techniques, while ignoring the class-wise mismatch across domains, resulting in inaccurate distribution alignment. To address this issue, we propose a *Joint Adversarial Domain Adaptation (JADA)* approach to simultaneously align domain-wise and class wise distributions across source and target in a unified adversarial learning process. Specifically, JADA attempts to solve two complementary minimax problems jointly. The feature generator aims to not only fool the well-trained domain discriminator to learn domain-invariant features, but also minimize the disagreement between two distinct task-specific classifiers’ predictions to synthesize target features near the support of source class-wisely. As a result, the learned transferable features will be equipped wit more discriminative structures, and effectively avoid mode collapse. Additionally, JADA enables an efficient end-to-end training manner via a simple back-propagation scheme. Extensive experiments on several real-world cross-domain benchmarks, including VisDA-2017, ImageCLEF, Office-31 and digits, verify that JADA can gain remarkable improvements over other state-of-the-art deep domain adaptation approaches.
---
title: "Discriminative Transfer Feature and Label Consistency for Cross-Domain Image Classification"
collection: publications
permalink: /publications/tnnls-dtlc
date: 2020-1-7
venue: "IEEE Transactions on Neural Networks and Learning Systems"
citation: "Shuang Li, Chi Harold Liu, Limin Su, Binhui Xie, Zhengming Ding, C. L. Philip Chen, and Dapeng Wu. Discriminative Transfer Feature and Label Consistency for Cross-Domain Image Classification. IEEE Transactions on Neural Networks and Learning Systems. doi: 10.1109/TNNLS.2019.2958152."


---

[[Paper]](https://ieeexplore.ieee.org/document/8951259) [[Code]](https://github.com/hnjzlishuang/DTLC)





## Abstract

Visual domain adaptation aims to seek an effective transferable model for unlabeled target images by benefiting from the well-labeled source images following different distributions. Many recent efforts focus on extracting domain-invariant image representations via exploring target pseudo labels, predicted by the source classifier, to further mitigate the conditional distri bution shift across domains. However, two essential factors are overlooked by most existing methods: 1) the learned transferable features should be not only domain invariant but also category discriminative; and 2) the target pseudo label is a two-edged sword to cross-domain alignment. In other words, the wrongly predicted target labels may hinder the class-wise domain matching. In this article, to address these two issues simultaneously, we propose a *discriminative transfer feature and label consistency (DTLC)* approach for visual domain adaptation problems, which can naturally unify cross-domain alignment with discriminative information preserved and label consistency of source and target data into one framework. To be specific, DTLC first incorporates class discriminative information by penalizing the maximum distance of data pair in the same class and the minimum distance of data pair sharing the different labels for each data into the distribution alignment of both domains. The target pseudo labels are then refined based on the label consistency within the domains. Thus, the transfer feature learning and coarse-to-fine target labels would be coupled to benefit each other in an iterative way. Comprehensive experiments on several visual cross-domain benchmarks verify that DTLC can gain remarkable margins over state-of-the-art (SOTA) nondeep visual domain adaptation methods and even be comparable to competitive deep domain adaptation ones.


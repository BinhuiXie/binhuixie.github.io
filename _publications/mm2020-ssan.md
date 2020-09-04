---
title: "Simultaneous Semantic Alignment Network for Heterogeneous Domain Adaptation"
collection: publications
permalink: /publications/mm20-ssan
date: 2020-10-12
venue: "ACM International Conference on Multimedia 2020"
citation: "Shuang Li, Binhui Xie, Jiashu Wu, Ying Zhao, Chi Harold Liu, and Zhengming Ding. Simultaneous Semantic Alignment Network for Heterogeneous Domain Adaptation. In ACM Multimedia. ACM, 2020."

---

[[Paper]](https://arxiv.org/abs/2008.01677) [[Code]](https://github.com/BIT-DA/SSAN)



## Abstract

Heterogeneous domain adaptation (HDA) transfers knowledge across source and target domains that present heterogeneities e.g., distinct domain distributions and difference in feature type or dimension. Most previous HDA methods tackle this problem through learning a domain-invariant feature subspace to reduce the discrepancy between domains. However, the intrinsic semantic properties contained in data are under-explored in such alignment strategy, which is also indispensable to achieve promising adaptability. In this paper, we propose a *Simultaneous Semantic Alignment Network (SSAN)* to simultaneously exploit correlations among categories and align the centroids for each category across domains. In particular, we propose an implicit semantic correlation loss to transfer the correlation knowledge of source categorical prediction distributions to target domain. Meanwhile, by leveraging target pseudo-labels, a robust triplet-centroid alignment mechanism is explicitly applied to align feature representations for each category. Notably, a pseudo label refinement procedure with geometric similarity involved is introduced to enhance the target pseudo-label assignment accuracy. Comprehensive experiments on various HDA tasks across text-to-image, image-to-image and text-to-text successfully validate the superiority of our SSAN against state-of-the-art HDA methods.


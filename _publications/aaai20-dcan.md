---
title: "Domain Conditioned Adaptation Network"
collection: publications
permalink: /publications/aaai20-dcan
date: 2020-2-7
venue: "AAAI Conference on Artificial Intelligence 2020"
citation: "Shuang Li, Chi Harold Liu, Qiuxia Lin, Binhui Xie, Zhengming Ding, Gao Huang, Jian Tang. Domain Conditioned Adaptation Network. In AAAI pages 11386–11393, 2020."


---

[[Paper]](https://aaai.org/ojs/index.php/AAAI/article/view/6801/6655) [[Code]](https://github.com/BIT-DA/DCAN)



## Abstract

Tremendous research efforts have been made to thrive deep domain adaptation (DA) by seeking domain-invariant features. Most existing deep DA models only focus on aligning feature representations of task-specific layers across domains while integrating a totally shared convolutional architecture for source and target. However, we argue that such strongly-shared convolutional layers might be harmful for domain-specific feature learning when source and target data distribution differs to a large extent. In this paper, we relax a shared-convnets assumption made by previous DA methods and propose a *Domain Conditioned Adaptation Network(DCAN)*, which aims to excite distinct convolutional channels with a domain conditioned channel attention mechanism. As a result, the critical low-level domain-dependent knowledge could be explored appropriately. As far as we know, this is the first work to explore the domain-wise convolutional channel activation for deep DA networks. Moreover, to effectively align high-level feature distributions across two domains, we further deploy domain conditioned feature correction blocks after task-specific layers, which will explicitly correct the domain discrepancy. Extensive experiments on three cross domain benchmarks demonstrate the proposed approach outperforms existing methods by a large margin, especially on very tough cross-domain learning tasks.


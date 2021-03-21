---
title: "Generalized Domain Conditioned Adaptation Network"
collection: publications
permalink: /publications/tpami-gdcan
date: 2021-3-1
venue: "IEEE Transactions on Pattern Analysis and Machine Intelligence (T-PAMI)"
citation: "Shuang Li, Binhui Xie, Qiuxia Lin, Chi Harold Liu, Gao Huang and Guoren Wang. Generalized Domain Conditioned Adaptation Network. In IEEE Transactions on Pattern Analysis and Machine Intelligence (T-PAMI), 2021."

---

[[Paper]](https://ieeexplore.ieee.org/document/9366353) [[Code]](https://github.com/BIT-DA/GDCAN)



## Abstract

Domain Adaptation (DA) attempts to transfer knowledge learned in the labeled source domain to the unlabeled but related target domain without requiring large amounts of target supervision. Recent advances in DA mainly proceed by aligning the source and target distributions. Despite the signifificant success, the adaptation performance still degrades accordingly when source and target domains encounter a large distribution discrepancy. We consider this limitation may attribute to insuffificient exploration of domain-specialized features, because most studies merely concentrate on domain-general feature learning in task-specific layers and integrate totally-shared convolutional networks (convnets) to generate common features for both domains. In this paper, we relax the completely-shared convnets assumption adopted by previous DA methods and propose *Domain Conditioned Adaptation Network (DCAN)*, which introduces domain conditioned channel attention module with multi-path structure to separately excite channel activation for each domain. Such a partially-shared convnets module allows domain-specialized features in low-level to be explored appropriately. Further, given the knowledge transferability varying along convolutional layers, we develop *Generalized Domain Conditioned Adaptation Network (GDCAN)* to automatically determine whether domain channel activations should be separately modeled in each attention module. Afterwards, the critical domain-specialized knowledge could be adaptively extracted according to the domain statistic gaps. As far as we know, this is the fifirst work to explore the domain-wise convolutional channel activations separately for deep DA networks. Additionally, to effectively match high-level feature distributions across domains, we additionally consider deploying feature adaptation blocks after task-specific layers, which is able to explicitly mitigate the domain discrepancy. Extensive experiments on four cross-domain benchmarks, including DomainNet, Offifice-Home, Offifice-31 and ImageCLEF, demonstrate the proposed approaches outperform the existing methods by a large margin, especially on the large-scale challenging dataset. The code and models are available at https://github.com/BIT-DA/GDCAN.


---
title: "Mapping in a cycle: Sinkhorn regularized unsupervised learning for point cloud shapes"
collection: publications
permalink: /publication/mapping-in-a-cycle
excerpt: 'An unsupervised learning framework with the pretext task of finding dense correspondences between point cloud shapes from the same category based on the cycle-consistency formulation.'
date: 2020-08-23
venue: 'European Conference on Computer Vision (2020)'
paperurl: 'https://arxiv.org/pdf/2007.09594.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Lei Yang, Wenxi Liu, Zhiming Cui, Nenglun Chen, Wenping Wang

**Abstract:** We propose an unsupervised learning framework with the pretext task of finding dense correspondences between point cloud shapes from the same category based on the cycle-consistency formulation. In order to learn discriminative pointwise features from point cloud data, we incorporate in the formulation a regularization term based on Sinkhorn normalization to enhance the learned pointwise mappings to be as bijective as possible. Besides, a random rigid transform of the source shape is introduced to form a triplet cycle to improve the model’s robustness against perturbations. Comprehensive experiments demonstrate that the learned pointwise features through our framework benefits various point cloud analysis tasks, e.g. partial shape registration and keypoint transfer. We also show that the learned pointwise features can be leveraged by supervised methods to improve the part segmentation performance with either the full training dataset or just a small portion of it.

[Project page and codes](https://github.com/LeiYangJustin/Map-in-a-Cycle)

[Download paper here](https://arxiv.org/pdf/2007.09594.pdf)

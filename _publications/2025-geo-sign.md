---
title: "Geo-Sign: Hyperbolic Contrastive Regularisation for Geometrically Aware Sign Language Translation"
collection: publications
category: preprint
permalink: /publication/2025-geo-sign
excerpt: 'This paper introduces Geo-Sign, a method that uses hyperbolic geometry to create more discriminative skeletal representations for Sign Language Translation, improving on SOTA methods while enhancing privacy and efficiency.'
date: 2025-05-30
venue: 'arXiv Preprint (Under Review)'
paperurl: 'https://arxiv.org/abs/2506.00129'
codeurl: 'https://github.com/ed-fish/geo-sign'
citation: 'Fish, E., & Bowden, R. (2025). &quot;Geo-Sign: Hyperbolic Contrastive Regularisation for Geometrically Aware Sign Language Translation.&quot; <i>arXiv preprint arXiv:2506.00129</i>.'
---

## Abstract

Recent progress in Sign Language Translation (SLT) has focussed primarily on improving the representational capacity of large language models to incorporate Sign Language features. This work explores an alternative direction: enhancing the geometric properties of skeletal representations themselves. We propose Geo-Sign, a method that leverages the properties of hyperbolic geometry to model the hierarchical structure inherent in sign language kinematics. By projecting skeletal features derived from Spatio-Temporal Graph Convolutional Networks (ST-GCNs) into the Poincaré ball model, we aim to create more discriminative embeddings, particularly for fine-grained motions like finger articulations. We introduce a hyperbolic projection layer, a weighted Fréchet mean aggregation scheme, and a geometric contrastive loss operating directly in hyperbolic space. These components are integrated into an end-to-end translation framework as a regularisation function, to enhance the representations within the language model. This work demonstrates the potential of hyperbolic geometry to improve skeletal representations for Sign Language Translation, improving on SOTA RGB methods while preserving privacy and improving computational efficiency.

---

<details>
<summary>BibTeX</summary>
<pre>
@article{fish2025geo,
  title={Geo-Sign: Hyperbolic Contrastive Regularisation for Geometrically Aware Sign Language Translation},
  author={Fish, Edward and Bowden, Richard},
  journal={arXiv preprint arXiv:2506.00129},
  year={2025}
}
</pre>
</details>

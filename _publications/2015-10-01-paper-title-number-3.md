---
title: "PLOT-TAL: Prompt Learning with Optimal Transport for Few-Shot Temporal Action Localization"
collection: publications
category: workshop
permalink: /publication/2025-plot-tal
excerpt: 'This paper introduces PLOT-TAL, a framework that uses multi-prompt ensembles and Optimal Transport to achieve state-of-the-art results in few-shot temporal action localization by learning compositional sub-events.'
date: 2025-07-24
venue: 'ICCV Workshop - Closing the Loop Between Vision and Language (CLVL) 2025'
paperurl: 'https://arxiv.org/abs/2403.18915'
citation: 'Fish, E., & Gilbert, A. (2025). &quot;PLOT-TAL: Prompt Learning with Optimal Transport for Few-Shot Temporal Action Localization.&quot; <i>Proceedings of the ICCV Workshop on Closing the Loop Between Vision and Language (CLVL)</i>.'
---

## Abstract

Few-shot temporal action localization (TAL) methods that adapt large models via single-prompt tuning often fail to produce precise temporal boundaries. This stems from the model learning a non-discriminative mean representation of an action from sparse data, which compromises generalization. We address this by proposing a new paradigm based on multi-prompt ensembles, where a set of diverse, learnable prompts for each action is encouraged to specialize on compositional sub-events. To enforce this specialization, we introduce PLOT-TAL, a framework that leverages Optimal Transport (OT) to find a globally optimal alignment between the prompt ensemble and the video's temporal features. Our method establishes a new state-of-the-art on the challenging few-shot benchmarks of THUMOS'14 and EPIC-Kitchens, without requiring complex meta-learning. The significant performance gains, particularly at high IoU thresholds, validate our hypothesis and demonstrate the superiority of learning distributed, compositional representations for precise temporal localization.

---

<details>
<summary>BibTeX</summary>
<pre>
@article{fish2025plot,
  title={PLOT-TAL--Prompt Learning with Optimal Transport for Few-Shot Temporal Action Localization},
  author={Fish, Edward and Gilbert, Andrew},
  journal={arXiv preprint arXiv:2403.18915},
  year={2025}
}
</pre>
</details>

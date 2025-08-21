---
title: "A Model for Every User and Budget: Label-Free and Personalized Mixed-Precision Quantization"
collection: publications
category: conference
permalink: /publication/2023-myqasr
excerpt: 'This paper introduces myQASR, a novel method for personalizing and compressing large ASR models for on-device deployment without fine-tuning, improving performance for specific users and languages.'
date: 2023-07-24
venue: 'Interspeech 2023'
paperurl: 'https://arxiv.org/abs/2307.12659'
citation: 'Fish, E., Michieli, U., & Ozay, M. (2023). &quot;A model for every user and budget: Label-free and personalized mixed-precision quantization.&quot; <i>Proceedings of the Annual Conference of the International Speech Communication Association (Interspeech)</i>.'
---

## Abstract

Recent advancement in Automatic Speech Recognition (ASR) has produced large AI models, which become impractical for deployment in mobile devices. Model quantization is effective to produce compressed general-purpose models, however such models may only be deployed to a restricted sub-domain of interest. We show that ASR models can be personalized during quantization while relying on just a small set of unlabelled samples from the target domain. To this end, we propose myQASR, a mixed-precision quantization method that generates tailored quantization schemes for diverse users under any memory requirement with no fine-tuning. myQASR automatically evaluates the quantization sensitivity of network layers by analysing the full-precision activation values. We are then able to generate a personalised mixed-precision quantization scheme for any pre-determined memory budget. Results for large-scale ASR models show how myQASR improves performance for specific genders, languages, and speakers.

---

<details>
<summary>BibTeX</summary>
<pre>
@article{fish2023model,
  title={A model for every user and budget: Label-free and personalized mixed-precision quantization},
  author={Fish, Edward and Michieli, Umberto and Ozay, Mete},
  journal={arXiv preprint arXiv:2307.12659},
  year={2023}
}
</pre>
</details>

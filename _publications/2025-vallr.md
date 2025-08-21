---
title: "VALLR: Visual ASR Language Model for Lip Reading"
collection: publications
category: conference
permalink: /publication/2025-vallr
excerpt: 'This paper introduces a novel, data-efficient, two-stage framework for lip reading that first predicts phonemes from video and then uses a Large Language Model to reconstruct sentences, achieving state-of-the-art results.'
date: 2025-07-01
venue: 'International Conference on Computer Vision (ICCV) 2025'
paperurl: 'https://arxiv.org/abs/2503.21408'
citation: 'Thomas, M., Fish, E., & Bowden, R. (2025). &quot;VALLR: Visual ASR Language Model for Lip Reading.&quot; <i>Proceedings of the International Conference on Computer Vision (ICCV)</i>.'
---

## Abstract

Lip Reading, or Visual Automatic Speech Recognition (V-ASR), is a complex task requiring the interpretation of spoken language exclusively from visual cues, primarily lip movements and facial expressions. This task is especially challenging due to the absence of auditory information and the inherent ambiguity when visually distinguishing phonemes that have overlapping visemes where different phonemes appear identical on the lips. Current methods typically attempt to predict words or characters directly from these visual cues, but this approach frequently encounters high error rates due to coarticulation effects and viseme ambiguity. We propose a novel two-stage, phoneme-centric framework for Visual Automatic Speech Recognition (V-ASR) that addresses these longstanding challenges. First, our model predicts a compact sequence of phonemes from visual inputs using a Video Transformer with a CTC head, thereby reducing the task complexity and achieving robust speaker invariance. This phoneme output then serves as the input to a fine-tuned Large Language Model (LLM), which reconstructs coherent words and sentences by leveraging broader linguistic context. Unlike existing methods that either predict words directly-often faltering on visually similar phonemes-or rely on large-scale multimodal pre-training, our approach explicitly encodes intermediate linguistic structure while remaining highly data efficient. We demonstrate state-of-the-art performance on two challenging datasets, LRS2 and LRS3, where our method achieves significant reductions in Word Error Rate (WER) achieving a SOTA WER of 18.7 on LRS3 despite using 99.4% less labelled data than the next best approach.

---

<details>
<summary>BibTeX</summary>
<pre>
@article{thomas2025vallr,
  title={VALLR: Visual ASR Language Model for Lip Reading},
  author={Thomas, Marshall and Fish, Edward and Bowden, Richard},
  journal={arXiv preprint arXiv:2503.21408},
  year={2025}
}
</pre>
</details>

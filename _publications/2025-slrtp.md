---
title: "SLRTP2025 Sign Language Production Challenge: Methodology, Results and Future Work"
collection: publications
category: workshop
permalink: /publication/2025-slrtp-challenge
excerpt: 'This paper presents the methodology and results of the first Sign Language Production Challenge, held at the SLRTP Workshop at CVPR 2025, establishing a new baseline for the field.'
date: 2025-06-01
venue: 'CVPR Workshop - Sign Language Recognition, Translation & Production (SLRTP) 2025'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2025W/SLRTP/html/Walsh_SLRTP2025_Sign_Language_Production_Challenge_Methodology_Results_and_Future_Work_CVPRW_2025_paper.html'
citation: 'Walsh, H., Fish, E., et al. (2025). &quot;SLRTP2025 Sign Language Production Challenge: Methodology, Results and Future Work.&quot; <i>Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops</i>.'
---

## Abstract

Sign Language Production (SLP) is the task of generating sign language video from spoken language inputs. The field has seen a range of innovations over the last few years, with the introduction of deep learning-based approaches providing significant improvements in the realism and naturalness of generated outputs. However, the lack of standardized evaluation metrics for SLP approaches hampers meaningful comparisons across different systems. To address this, we introduce the first Sign Language Production Challenge, held as part of the third SLRTP Workshop at CVPR 2025. The competition's aims are to evaluate architectures that translate from spoken language sentences to a sequence of skeleton poses, known as Text-to-Pose (T2P) translation, over a range of metrics. For our evaluation data, we use the RWTH-PHOENIX-Weather-2014T dataset, a German Sign Language - Deutsche Gebardensprache (DGS) weather broadcast dataset. In addition, we curate a custom hidden test set from a similar domain of discourse. This paper presents the challenge design and the winning methodologies. The challenge attracted 33 participants who submitted 231 solutions, with the top-performing team achieving BLEU-1 scores of 31.40 and DTW-MJE of 0.0574. The winning approach utilized a retrieval-based framework and a pre-trained language model. As part of the workshop, we release a standardized evaluation network, including high-quality skeleton extraction-based keypoints, establishing a consistent baseline for the SLP field, which will enable future researchers to compare their work against a broader range of methods.

---

<details>
<summary>BibTeX</summary>
<pre>
@inproceedings{walsh2025slrtp2025,
  title={SLRTP2025 Sign Language Production Challenge: Methodology, Results and Future Work},
  author={Walsh, Harry and Fish, Ed and Sincan, Ozge Mercanoglu and Lakhal, Mohamed Ilyes and Bowden, Richard and Fox, Neil and Woll, Bencie and Wu, Kepeng and Li, Zecheng and Zhao, Weichao and others},
  booktitle={Proceedings of the Computer Vision and Pattern Recognition Conference},
  pages={4109--4119},
  year={2025}
}
</pre>
</details>

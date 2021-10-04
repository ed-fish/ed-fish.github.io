---
layout: page
title: Semantic Video Embedding Visualisation
description: An interactive website for exploring embedding projections. 
img: /assets/img/semantic-embedding.jpg
importance: 2
category: work
img: /assets/img/embed1.PNG
---

A visualisation of the results from our latest paper [Rethinking Genre Classification With Fine Grained Semantic Clustering](https://ieeexplore.ieee.org/document/9506751). The website features both UMAP and T-SNE projections of the self-supervised fine-grained embedding space generated from the model. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/embed1.PNG' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/embed2.PNG' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/embed3.PNG' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Left. View embeddings in UMAP, Middle: TSNE, and Right: Rasterfy. 

Due to storage limitations, the videos are embedded via YouTube and the free tier has a very limited number of API calls per a day. You may need to check back the next day if all API requests have been made.

Checkout the code [here](https://github.com/ed-fish/semantic-video-visualiser)
```

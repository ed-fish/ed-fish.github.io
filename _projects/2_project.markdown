---
layout: page
title: Semantic Video Embedding Visualisation
description: An interactive website for exploring embedding projections. 
img: /assets/img/semantic-embedding.jpg
importance: 2
category: work
img: /assets/img/embed1.PNG
---

An interactive visualisation of the results from our latest paper [Rethinking Genre Classification With Fine Grained Semantic Clustering](https://ieeexplore.ieee.org/document/9506751). The website features both UMAP and T-SNE projections of the self-supervised fine-grained embedding space generated from the model. 

Visit the page [here](https://semantic-video-visualiser-g6n4qaxte-ed-fish.vercel.app/#)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/embed1.PNG' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    T-SNE visualisation.
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/embed2.PNG' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Samples with the ID "animation" selected
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/embed3.PNG' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    UMAP visualisation
    </div>

Please note: there is an issue retrieving videos due to API request limitations - this will be fixed shortly. 

Checkout the code used to generate the visualisation [here](https://github.com/ed-fish/semantic-video-visualiser)




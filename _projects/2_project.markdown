---
layout: page
title: Semantic Video Embedding Visualisation
description: An interactive website for exploring embedding projections. 
img: /assets/img/semantic-embedding.jpg
importance: 2
category: work
img: /assets/img/embed1.PNG
---

Another experiment where I've applied my research to a real world application. This time I took embeddings generated from my paper: [Rethinking Genre Classification With Fine Grained Semantic Clustering](https://ieeexplore.ieee.org/document/9506751) and built an application for feature projection and exploration. The website features both UMAP and T-SNE projections of the self-supervised fine-grained embedding space generated from the model and also some additional cool features such as selecting videos of specific genres and dates. 

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

Please note: there is a small bug where you have to select a video twice for the video to load correctly because of API request limitations. 

If you'd like to edit the code for your own embeddings you can find the code [here](https://github.com/ed-fish/semantic-video-visualiser)




---
layout: page
title: Video Recommendation App
description: Find a similar movie based only on its audio-visual content
img: /assets/img/recommendation-app.PNG
importance: 2
category: work
img: /assets/img/recommendation-app.PNG
---

A very basic video recommendation application I created to try out both Spotify's ANNOY library for approximate nearest neighbour search and StreamLit. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/recommendation-app-2.png' | relative_url }}" alt="" title="recommendation 1"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/recommendation-app-3.png' | relative_url }}" alt="" title="recommendation 2"/>
    </div>
</div>
<div class="caption">
    A quick prototytpe to explore some new frameworks.  
</div>

If you haven't heard of ANNOY - it's a library for finding k nearest neighbours using binary search 0(log n).   
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="https://erikbern.com/assets/2015/09/heap-pos-1024x793.png" alt="" title="annoy hyperplane"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="https://camo.githubusercontent.com/a056535a8490b4b1aa933808e77207276235a209e97a980119d3e438897e1d36/68747470733a2f2f7261772e6769746875622e636f6d2f73706f746966792f616e6e6f792f6d61737465722f616e6e2e706e67" alt="" title="annoy hyperplane"/>
    </div>
</div>
<div class="caption">
    ANNOY takes random projections and builds a tree. At every intermediate node in the tree, a random hyperplane is chosen, which divides the space into two subspaces. This hyperplane is chosen by sampling two points from the subset and taking the hyperplane equidistant from them.
</div>

As an experiment I created a basic transformer attention network (like ViViT) but used pre-trained convolutional networks to encode scenes from movie trailers rather than mapping attention at a pixel level.
I used a pretrained I3D model (Kinetics 400) network to get a temporal feature for every 16 frames and a pretrained ResNet (Imagenet) to encode spatial data for every scene.   

These are passed through the transformer encoder and then a linear layer to obtain an embedding vecor. I then added a projection head for classification which will be removed after training.  

I trained the model for 50 epochs on a genre classifcation task - actually achieving SOTA on the MMX dataset with 57% accuracy over 15 labels.

To view the results I wrote a quick streamlit application which can be viewed [here](https://share.streamlit.io/ed-fish/trailer-recommendation-engine/main/app.py)

Check it out [here](https://share.streamlit.io/ed-fish/trailer-recommendation-engine/main/app.py)





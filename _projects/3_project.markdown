---
layout: page
title: Video Recommendation App
description: Find a similar movie based only on its audio-visual content
img: /assets/img/recommendation-app.PNG
importance: 2
category: work
img: /assets/img/recommendation-app.PNG
---

I was interested in trying out Spotify's [ANNOY](https://github.com/spotify/annoy) library for approximate nearest neighbour search - The "oh yeah!" part of the acronym is well deserved as it really is lightning fast.  

If you haven't heard of ANNOY - it's a library for finding k nearest neighbours using binary search 0(log n).   
<br>
<div class="row">
        <img class="img-fluid rounded z-depth-1" src="https://camo.githubusercontent.com/a056535a8490b4b1aa933808e77207276235a209e97a980119d3e438897e1d36/68747470733a2f2f7261772e6769746875622e636f6d2f73706f746966792f616e6e6f792f6d61737465722f616e6e2e706e67" alt="" title="annoy image"/>
</div>
<div class="caption">
    ANNOY takes random projections and builds a tree. At every intermediate node in the tree, a random hyperplane is chosen, which divides the space into two subspaces. This hyperplane is chosen by sampling two points from the subset and taking the hyperplane equidistant from them.
</div>
<br>
As an experiment I created a basic transformer attention network (like ViViT) but used pre-trained convolutional networks to encode scenes from movie trailers rather than mapping attention at a pixel level.
I used a pretrained I3D model (Kinetics 400) network to get a temporal feature for every 16 frames and a pretrained ResNet (Imagenet) to encode spatial data for every scene.   
<br>
These are passed through the transformer encoder and then a linear layer to obtain an embedding vecor. I then added a projection head for classification which will be removed after training.  

I trained the model for 50 epochs on a genre classifcation task - actually achieving SOTA on the MMX dataset with 57% accuracy over 15 labels.

To view the results I wrote a quick streamlit application which can be viewed [here](https://share.streamlit.io/ed-fish/trailer-recommendation-engine/main/app.py)

<br>
<div class="row">
        <img class="img-fluid rounded z-depth-1" src="/assets/img/recommendation-app.PNG" alt="" title="app interface"/>
</div>
<div class="caption">
    Using just the visual features results in relatively accurate recommendations.
</div>
<br>
Check it out [here](https://share.streamlit.io/ed-fish/trailer-recommendation-engine/main/app.py)





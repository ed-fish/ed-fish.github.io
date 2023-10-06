---
layout: page
title: Style-Based Movie Recommendation App
description: Find movies with similar styles.
img: /assets/img/recommendation-app.PNG
importance: 2
category: work
img: /assets/img/recommendation-app.PNG
---

One thing I really like to do after writing a paper is to try incorporating my research into a real application. This little reccomendation engine uses my two-stream transformer architecture for long form video understanding (BMVC 22) to generate embedding features. The cool thing about this is that it only uses audio-visual information to cluster the movies so it incorporates more stylistic features, rather than the usual method for clustering films using pre-defined tags. I think this makes quite a cool recomendation system that offers more fine-grained representations that capture some of the cinemetography of the movie. 

It's pretty fast too since I bootstrapped the Spotify ANNOY library for k nearest neighbours on the embeddings (0(log_n)).

Check it out [here](https://share.streamlit.io/ed-fish/trailer-recommendation-engine/main/app.py)





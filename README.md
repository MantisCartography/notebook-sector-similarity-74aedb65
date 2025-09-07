# Sector Similarity

Created by lbvoros@gmail.com for [space](https://mantisdev.csail.mit.edu/space/b01c3fe1-bbda-402a-a430-ea4c721cf9cb/)

## Description

This code snippet computes and visualizes the pairwise cosine similarity between sectors based on their raw embeddings. It uses `defaultdict` to accumulate embeddings corresponding to different sectors and calculates their average. The `cosine_similarity` function is defined to compute similarities between embedding vectors. The main portion of the code normalizes these vectors and constructs a similarity matrix, which is then displayed as a heatmap using Matplotlib, showing the cosine similarity scores between sectors.

### Note
notebook.ipynb isn't a valid ipynb. We append the extension for GitHub rendering purposes.
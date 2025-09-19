# Sector Similarity

Created by lbvoros@gmail.com for [space](https://mantisdev.csail.mit.edu/space/b01c3fe1-bbda-402a-a430-ea4c721cf9cb/)

## Description

This code snippet processes and visualizes sector embeddings and their pairwise cosine similarities in a React component.

1. **Data Aggregation**: It first computes average embeddings for different sectors using a series of nested loops, which populate dictionaries with embeddings and counts.

2. **Cosine Similarity Calculation**: The `cosine_similarity` function computes the similarity between two vectors, followed by calculating pairwise similarities for all sector embeddings.

3. **Heatmap Visualization**: Using `matplotlib`, a heatmap is built from the pairwise similarity matrix, displaying sector similarities visually, along with textual annotations.

4. **React Component**: The `SectorSimilarity` React component manages state for selected sectors, visualization modes, and user interactions. It presents a heatmap, similarity lists, and detailed vector comparisons.

5. **Histogram Function**: A utility function generates a histogram of similarity distributions, offering visual insights into the data.

6. **Widget Integration**: Concludes by creating an instance of the similarity component and adding it to the UI, enabling a dynamic interface for exploring sector relationships within the cognitive mapping platform.

### Note
notebook.ipynb isn't a valid ipynb. We append the extension for GitHub rendering purposes.
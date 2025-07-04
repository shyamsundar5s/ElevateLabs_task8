# ElevateLabs_task8
# Image Compression with K-means Clustering
This project demonstrates how to use K-means clustering for compressing images by reducing the number of unique colors, implemented in a Jupyter Notebook.

## Overview
In this notebook, we leverage the K-means clustering algorithm from `scikit-learn` to perform unsupervised learning for image compression. By clustering similar colors together, we can represent an image using far fewer colors with minimal perceptual loss, resulting in significant compression.

**Key Steps:**
- Load an RGB image and preprocess the pixel data.
- Apply K-means clustering to group pixels into K clusters (colors).
- Reconstruct the compressed image using the cluster centroids.
- Visualize and compare the original and compressed images for different values of K.

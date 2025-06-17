# Image Compression using K-Means Clustering 

![img alt](https://github.com/jayanth142006/image-resolution-compression-ML/blob/0780a61926612f69698c2143c945f76da2d888c7/Screenshot%202025-06-17%20230623.png)

This project implements image compression using K-Means clustering built entirely from scratch in Python (without using scikit-learn). It works by:

Flattening image pixels and clustering them into K color centroids.

Replacing each pixel with its nearest centroid, reducing the number of unique colors.

Visualizing compressed results using Matplotlib in a grid for different K values.

🔧 Highlights:

Manual implementation of centroid initialization, distance calculation, and convergence logic.

Grid display of original and compressed images for comparison.

📦 Libraries Used:

NumPy

Matplotlib

PIL

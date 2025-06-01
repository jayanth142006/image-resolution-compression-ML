# Image Compression using K-Means Clustering (from Scratch)
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

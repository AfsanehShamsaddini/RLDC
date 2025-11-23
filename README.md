🌟 RLDC: Robust Local Density Clustering

Authors: Afsaneh Shamsaddini-Farsangi & Mostafa Ghazizadeh-Ahsaee
Shahid Bahonar University of Kerman, Iran
📧 ashamsadini29@gmail.com
 | mghazizadeh@uk.ac.ir

🔍 What is RLDC?

RLDC (Robust Local Density Clustering) is a smart clustering algorithm designed for datasets with clusters of varying densities.

It combines:

⚡ Local density estimation

🌐 Fuzzy k-Nearest Neighbors (k-NN)

📏 Mahalanobis distance for better accuracy

🚫 Outlier detection using LOF

🎯 Why use RLDC?

Handles multi-density clusters

Automatically detects and removes outliers

Assigns soft memberships via fuzzy k-NN

Can automatically select the best k (number of neighbors)

⏳ Code Availability

The implementation of RLDC will be publicly available after the paper is published.
Please check back here for the full code and examples.

📖 Paper Reference
Afsaneh Shamsaddini-Farsangi, Mostafa Ghazizadeh-Ahsaee
"Robust Local Density Clustering with Weighted Similarity Neighbors for Multi-Density Data"
[Journal/Conference Name], 2025

⚡ Quick Overview (Algorithm Steps)

Standardize the dataset

Detect and remove outliers using LOF

Compute fuzzy memberships using k-NN and Mahalanobis distance

Estimate local density for each point

Identify cluster centers based on density and distance

Assign remaining points to clusters using neighbors

📝 Future Updates

Full Python implementation

Example notebooks for synthetic and real datasets

Pre-built requirements.txt for easy setup

Stay tuned! 🚀

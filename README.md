
# Netflix Movies and TV Shows Clustering Project

# Project Overview

This project delved into the world of Netflix shows, using text clustering techniques to unlock hidden connections. The goal was to group shows based on their descriptions, ensuring that those within a cluster share similar themes, genres, or styles. This approach helps explore the vast Netflix library more effectively and identify shows viewers might enjoy based on their past preferences.

# Content Treasure Trove

# Dataset
7,787 records, each described by 11 informative attributes.

# Data Preparation & Exploration
Data Cleaning: Started by cleaning the dataset to ensure accuracy and reliability.

Exploratory Data Analysis (EDA): Performed EDA to gain insights into the Netflix shows and movies, revealing that Netflix has more movies than TV shows, with new shows rapidly joining the platform. Interestingly, US-made content dominates the show selection.

# Untangling the Netflix Universe

# Text Clustering Techniques
Key Attributes: Focused on attributes like cast, genre, and director.

TF-IDF Transformation:  Transformed these details into numerical data using TF-IDF, making it easier to reveal hidden connections.

Principal Component Analysis (PCA)

Dimensionality Reduction: Addressed the "curse of dimensionality" by employing PCA, which identified the most important features.

Streamlined Data: Reduced 10,000 features to 3,000 components that retained over 80% of the information, empowering our analysis to find hidden relationships between shows.

# Finding the Perfect Fit
K-Means Clustering

Optimal Clusters: Used the elbow method and silhouette score to determine that 6 clusters provided the most optimal fit for organizing Netflix shows.

Hierarchical Clustering

Natural Groupings: Explored hierarchical clustering to discover natural groupings. By examining the dendrogram, identified 7 optimal clusters, offering an alternative perspective on the Netflix show landscape.

# Finding Your Next Binge
Content-Based Recommendation System

Cosine Similarity: Built a recommendation system using cosine similarity to analyze show descriptions and recommend 10 similar options based on what users have watched before, helping them discover hidden gems they'll love.

# Conclusion
This project highlights the power of text clustering techniques in unlocking hidden connections within the Netflix library. By leveraging TF-IDF, PCA, K-Means, and hierarchical clustering, we provided valuable insights into show similarities and developed a content-based recommendation system to enhance user experience.




# Spotify Hits — Unsupervised Learning Challenge

A data science challenge exploring **patterns in popular music** using **unsupervised learning** techniques on Spotify’s track features dataset.  
The goal of this project is to uncover **hidden structures** in music data — such as genre similarities, popularity clusters, and relationships between audio features — without using any predefined labels.

---

## Project Overview

This challenge aims to apply **unsupervised learning** (clustering and dimensionality reduction) to understand what makes a song a "hit" on Spotify.

By analyzing acoustic features such as **energy, valence, tempo, danceability, and loudness**, this project identifies **clusters of songs** that share similar patterns and explores their connection with song popularity.

---

## Objectives

- Perform **data preprocessing** and **feature engineering** on Spotify tracks  
- Apply **dimensionality reduction** to visualize the data in 2D  
- Use **clustering algorithms** to find structure in the data  
- Interpret clusters based on **audio features and popularity metrics**  
- Visualize and explain what differentiates “hit songs” from others  

---

## Tools & Technologies

| Category | Tools |
|-----------|-------|
| **Language** | Python |
| **Data Handling** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **Machine Learning** | Scikit-learn  |
| **Evaluation** | Silhouette Score, Elbow Method |

---

## Dataset

The dataset contains Spotify song-level metadata and acoustic features:
- `danceability`
- `energy`
- `valence`
- `acousticness`
- `instrumentalness`
- `speechiness`
- `tempo`
- `duration_ms`
- `popularity` .....

Each row corresponds to one track.  
The data is preprocessed to remove missing values, scale features, and standardize numerical columns.

---

## Methodology

1. **Data Cleaning & Exploration**
   - Inspected missing values, outliers, and correlations.
   - Visualized feature distributions and pairwise relationships.

2. **Feature Scaling**
   - Applied **StandardScaler** to normalize numerical data.

3. **Dimensionality Reduction**
   - Used **PCA** to reduce feature space while preserving variance.
   - Experimented with **t-SNE** for non-linear feature projection.

4. **Clustering**
   - Applied **K-Means** and optimized the number of clusters using the **Elbow Method**.
   - Compared with **DBSCAN** and **Agglomerative Clustering** for better interpretability.

5. **Cluster Analysis**
   - Analyzed mean values of features per cluster.
   - Interpreted cluster differences in terms of musical attributes.

6. **Visualization**
   - Generated 2D plots of clusters in PCA/t-SNE space.
   - Visualized relationships between energy, danceability, and popularity.

---

## Key Insights

- Songs with **high energy and danceability** tend to form a distinct “hit” cluster.  
- **Acoustic and instrumental tracks** often cluster together due to low energy and high acousticness.  
- The **valence-energy relationship** highlights emotional tone differences between clusters (happy vs. moody songs).  
- PCA visualization reveals overlapping regions between pop and electronic genres, showing musical fusion trends.

---

## 🧪 Results

| Algorithm | Number of Clusters | Silhouette Score |
|------------|-------------------|------------------|

The ** ... algorithm** provided the best interpretability and cluster separation based on audio features.

---

## Future Work



---

⭐ *Exploring the hidden structure of music through data science and unsupervised learning.*

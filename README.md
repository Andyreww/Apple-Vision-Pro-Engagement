# Twitter Engagement Analysis on Apple Vision Pro 

![Apple Vision Pro](/VP.png)

## Overview

This project uses **K-Means clustering algorithm** to analyze engagement metrics on tweets related to the **Apple Vision Pro**. The study aims to uncover patterns in user interaction and provides insights by categorizing engagement into **low, moderate, and high levels**.

---

## Data Description

The dataset was obtained from Kaggle and consists of Twitter engagement metrics, including:

- **Reply Count**
- **Quote Count**
- **Retweet Count**
- **Like Count**
- **Views**
- **Bookmark Count**

---

## Preprocessing Steps

1. **Handling Missing Values**: Removed rows with missing engagement data.
2. **Normalization**: Scaled metrics using Min-Max normalization to ensure balanced clustering.
3. **Feature Selection**: Focused on key metrics for clustering and visualization.

---

## K-Means Algorithm

The K-Means algorithm grouped tweets into **3 clusters**:

1. **Cluster 0**: Low engagement (minimal interactions).
2. **Cluster 1**: Moderate engagement (casual user interest).
3. **Cluster 2**: High engagement (influential tweets with significant interaction).

---

## Visualizations

The clustering outcomes were visualized using **2D scatter plots** based on pairs of normalized features:

- **Like Count vs. Retweet Count**
- **Reply Count vs. Quote Count**
- **Views vs. Bookmark Count**

---

## Results and Interpretation

| **Cluster** | **Reply Count** | **Retweet Count** | **Like Count** | **Views**     | **Bookmark Count** |
|-------------|----------------|------------------|---------------|--------------|-------------------|
| Low         | 0.86           | 1.51             | 8.02          | 1,400        | 0.63              |
| Moderate    | 142.00         | 2,443.00         | 9,984.67      | 1.72M        | 1,018.00          |
| High        | 150.70         | 206.48           | 1,165.22      | 204,000      | 82.61             |

---

## Conclusion

The clustering reveals how **influential users** shape public discourse. This insight can guide companies like Apple in **partnering with influencers** and optimizing their content strategy. Marketing teams can leverage these findings to enhance **engagement and outreach**.

---
   

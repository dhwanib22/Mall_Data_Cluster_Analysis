# Mall Data Cluster Analysis

## Introduction

This repository explores cluster analysis on mall data with the goal of understanding customer behavior and grouping similar individuals.

## Agenda

1. **EDA:** Perform Exploratory Data Analysis to understand the dataset's structure, identify patterns, and gain insights into customer attributes.

2. **Visualization:** Utilize visualizations with proper explanations to provide a clear understanding of the data distribution, correlations, and trends.

3. **Cluster Analysis:** Employ different clustering algorithms to group customers based on their attributes. Assign meaningful names to each cluster to interpret the characteristics of the identified groups.

## Data

mall_data.csv: Contains customer attributes, including ID, income, mall visits, and six additional features (V1-V6).

### Attributes Description

- **ID:** Unique customer ID.
- **V1, V2, V3, V4, V5, V6:** Integer attributes.
- **Income:** Income of each unique customer (float).
- **Mall Visits:** Number of visits to the mall (int).

## Models

The following clustering algorithms are used:

1. **Agglomerative Clustering:** A hierarchical clustering method that successively merges similar clusters.
   
2. **K-Means Clustering:** A partitioning method that divides the dataset into 'k' clusters based on centroids.

3. **DB Scan (Density-Based Spatial Clustering of Applications with Noise):** A density-based method that groups together data points that are close to each other.


## Conclusion

This repository serves as a comprehensive analysis of mall customer data, providing valuable insights through EDA, visualizations, and cluster analysis. The results aim to enhance our understanding of customer segments, enabling businesses to tailor strategies for different clusters. Contributions and improvements are welcome.

Feel free to raise issues or submit pull requests for enhancements. Happy clustering!

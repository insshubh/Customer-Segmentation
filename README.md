# Customer Segmentation

Welcome to the Customer Segmentation project! This project aims to segment customers based on their spending behavior and demographics using K-Means clustering.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [Usage](#usage)

## Introduction

Customer segmentation is a crucial aspect of marketing strategy. By understanding the different segments of customers, businesses can tailor their marketing efforts to meet the needs of specific groups more effectively. This project uses K-Means clustering to segment customers into distinct groups based on their spending behavior and demographics.

## Dataset

The dataset used for this project contains the following columns:

- `CustomerID`: Unique ID for each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousand dollars
- `Spending Score (1-100)`: A score assigned to the customer based on their spending behavior
- `Work Experience`: Number of years of work experience
- `Family Size`: Size of the customer's family

The dataset can be found in the repository as `Mall_Customers.csv`.

## Methodology

1. **Data Preprocessing**:
    - Handling missing values
    - Encoding categorical variables
    - Standardizing numerical features

2. **Exploratory Data Analysis (EDA)**:
    - Visualizing the distribution of features
    - Analyzing correlations between features

3. **Clustering with K-Means**:
    - Choosing the optimal number of clusters using the Elbow method
    - Fitting the K-Means algorithm to the data
    - Visualizing the clusters

## Results

The K-Means algorithm segmented the customers into distinct clusters based on their spending behavior and demographics. Each cluster represents a group of customers with similar characteristics. The segments can be used to tailor marketing strategies and improve customer engagement.

### Cluster Characteristics

- **Cluster 1**: Young customers with low income and high spending scores
- **Cluster 2**: Older customers with high income and moderate spending scores
- **Cluster 3**: Middle-aged customers with moderate income and low spending scores
- **Cluster 4**: Young customers with high income and high spending scores
- **Cluster 5**: Older customers with low income and low spending scores

### Visualizations

- **Cluster Scatter Plots**: Visualizing the clusters in a 2D space based on different feature combinations.
- **Box Plots**: Analyzing the distribution of features within each cluster.
- **Heatmaps**: Showing the correlation between features.

## Conclusion

The customer segmentation analysis provides valuable insights into the different customer groups. These insights can help businesses develop targeted marketing strategies, improve customer satisfaction, and increase sales.

## Usage

To run the analysis on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/insshubh/Customer-Segmentation.git

  Made by Shubham Kumar

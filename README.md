# Customer Segmentation with Clustering Techniques

This project demonstrates customer segmentation using clustering techniques in Python. The primary focus is on using **K-Means Clustering** (with optional PCA for dimensionality reduction) to segment mall customers based on their demographics and spending behavior. The solution includes full data preprocessing, exploratory data analysis (EDA), model building, and visualization of the resulting clusters.

## Overview

Customer segmentation is an essential process for businesses to understand their customer base and target specific groups with marketing strategies. In this project, we use clustering algorithms to identify distinct groups of customers based on features such as:

- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Dataset

The dataset used is the popular **Mall Customers** dataset, which contains the following columns:

- `CustomerID`: Unique ID for each customer
- `Genre`: Gender of the customer (Male/Female)
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income in thousands of dollars
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending

## Key Steps

1. **Import Libraries**:
   - pandas, numpy, matplotlib, seaborn
   - scikit-learn for clustering and preprocessing

2. **Load and Explore Data**:
   - Read dataset
   - Explore data shape, summary statistics, and check for missing values

3. **Preprocessing**:
   - Drop irrelevant columns (e.g., CustomerID)
   - Encode categorical features (e.g., Gender)
   - Standardize features

4. **EDA & Visualization**:
   - Univariate and bivariate analysis
   - Pairplot for feature relationships

5. **Clustering**:
   - Use K-Means algorithm
   - Determine optimal number of clusters (Elbow method)
   - Optionally apply PCA for visualization in 2D

6. **Results & Visualization**:
   - Visualize clusters using scatter plots
   - Analyze characteristics of each cluster

## Requirements

- Python 3.x
- Jupyter Notebook or Google Colab
- pandas, numpy, matplotlib, seaborn
- scikit-learn

Install requirements via pip if needed:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. **Clone the repository** or download the notebook and dataset files.
2. **Open** `Customer_Segmentation_with_Clustering_Techniques.ipynb` in Jupyter Notebook or Google Colab.
3. **Run each cell sequentially** to follow the workflow, from data loading to cluster visualization.

## Results & Visualization

- The project visualizes customer clusters using scatter plots.
- Plots show how customers are grouped based on income and spending score, and how demographic features relate to clusters.
- Insights can be used for targeted marketing and business strategy.


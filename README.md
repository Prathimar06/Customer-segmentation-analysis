# Customer Segmentation Using Machine Learning

## Overview
Customer segmentation is the process of dividing customers into groups based on similar characteristics or behavior. In this project, customer data is analyzed and segmented using unsupervised machine learning techniques to discover meaningful customer groups. The main objective of this project is to understand customer purchasing patterns and classify customers into segments that can be useful for marketing strategy, customer retention, and business decision-making.

## Problem Statement
Organizations collect large amounts of customer data but often struggle to convert this data into actionable insights. The goal of this project is to group customers based on similarity, identify high-value and low-value customer segments, and analyze customer behavior using clustering algorithms.

## Dataset
The dataset contains customer-related numerical features representing purchasing behavior. It is used as input for clustering algorithms to identify similar customers.

Dataset path:
data/customer_data.xlsx

## Technologies and Tools Used
Python, Jupyter Notebook, Pandas, NumPy for data preprocessing and analysis, Matplotlib and Seaborn for visualization, and Scikit-learn for implementing machine learning algorithms.

## Machine Learning Algorithms Implemented
K-Means Clustering is used to partition customers into a predefined number of clusters and group customers with similar spending behavior. DBSCAN is a density-based clustering technique that helps identify noise points and outliers in customer data. Hierarchical Clustering creates a hierarchy of clusters and is visualized using dendrograms to understand relationships between clusters.

## Project Workflow
The project follows these steps: data loading and inspection, data preprocessing and normalization, feature selection, applying clustering algorithms, visualizing clusters, and interpreting and analyzing results.

## Results and Observations
Customers were successfully segmented into meaningful groups. One cluster represents high-value customers with higher spending behavior, while another cluster represents low-engagement customers. DBSCAN identified a few outlier customers that do not belong to any major cluster. Hierarchical clustering provided a clear visual structure of customer relationships. Output visualizations generated during analysis are stored in the outputs folder.

## Key Learnings
This project helped in gaining practical understanding of unsupervised machine learning, comparing different clustering algorithms on the same dataset, interpreting clustering results for real-world business scenarios, and understanding the importance of feature scaling in clustering problems.

## How to Run the Project
Clone the repository using: git clone https://github.com/Prathimar06/Customer-segmentation-analysis.git  
Install required dependencies using: pip install pandas numpy matplotlib seaborn scikit-learn  
Launch Jupyter Notebook using: jupyter notebook  
Open and run the notebook: notebooks/customer_segmentation_analysis.ipynb

## Note on Originality
This project is inspired by publicly available resources. The implementation, execution, analysis, visualizations, and documentation were performed independently for learning and demonstration purposes.

## Future Enhancements
Future improvements include adding silhouette score and elbow method comparison, applying PCA for dimensionality reduction, testing clustering performance on a larger dataset, and integrating results into a simple dashboard.

## Author
Prathima Rangavajjula  
Engineering Student 

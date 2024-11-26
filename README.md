# Shopping Mall-Customer-Segmentation

# Overview
Customer segmentation is an essential process in marketing and analytics to categorize customers based on shared characteristics. This project employs K-Means Clustering to segment customers into distinct groups based on their Annual Income (in $k) and Spending Score (scale of 1-100).

# Project Insights
The output plot represents a bivariate clustering analysis:

* The X-axis represents Annual Income (in $k).
* The Y-axis represents the Spending Score (scale of 1-100).
* The points are grouped into five clusters, each representing a unique customer segment:
* Cluster 0 (Blue): Average earners with moderate spending.
* Cluster 1 (Orange): High-income earners with high spending.
* Cluster 2 (Green): High-income earners with low spending.
* Cluster 3 (Red): Low-income earners with low spending.
* Cluster 4 (Purple): Low-income earners with high spending.
* The black stars represent the centroids of each cluster, indicating the central tendency of each group.
  
# Key Features

### Data Preprocessing:

* Handled missing or erroneous values.
* Standardized features to ensure clustering accuracy.
  
### Clustering Algorithm:

* Implemented K-Means Clustering.
* Determined the optimal number of clusters using the Elbow Method.
  
### Visualization:

* Created a scatter plot to display clusters with distinct colors and centroids.

# Technologies Used

**Language:** Python
**IDE:** Google Colab

# Libraries:

**pandas:** For data manipulation and preprocessing.
**matplotlib:** For data visualization.
**seaborn:** For aesthetic enhancements in visualization.
**scikit-learn:** For implementing the K-Means algorithm.

# Project Structure

Shopping_Mall_Customer_Segmentation.ipynb: Jupyter Notebook containing the code implementation.
Bivariate Clustering.png: Output visualization of the clusters.
Shopping_Mall_Customer_Segmentation.csv: Input dataset containing customer information (Annual Income and Spending Score).
README.md: Project description and details (this file).

Conclusion
This project demonstrates how clustering can uncover valuable insights for customer segmentation. The application of K-Means is a robust approach for analyzing customer data and making data-driven decisions.


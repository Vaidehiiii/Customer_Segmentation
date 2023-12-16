# Customer_Segmentation

**Project Title: Customer Segmentation with K-means Clustering**

**Project Overview:**

This project utilizes K-means clustering to analyze and categorize customer data from a mall. The dataset includes information such as customer demographics, annual income, and spending scores. The primary objectives are to explore the dataset, determine the optimal number of clusters, train a K-means clustering model, and visualize the results.

**Project Structure:**

1. **Dependencies:**
   - numpy
   - pandas
   - matplotlib
   - seaborn
   - scikit-learn

2. **Data Collection & Analysis:**
   - The dataset, 'Mall_Customers.csv,' is loaded into a Pandas DataFrame.
   - Basic exploratory data analysis is performed, including a summary of the dataset and checking for missing values.

3. **Choosing Features:**
   - The "Annual Income" and "Spending Score" columns are selected for clustering.

4. **Choosing the Number of Clusters:**
   - The Within Clusters Sum of Squares (WCSS) is calculated for different numbers of clusters.
   - An elbow graph is plotted to determine the optimal number of clusters (in this case, 5).

5. **Training the K-means Model:**
   - A K-means clustering model with 5 clusters is trained on the selected features.

6. **Visualizing Clusters:**
   - The clusters are visualized on a scatter plot, with each cluster assigned a unique color.
   - Centroids of the clusters are also plotted for additional insights.

# 🍽️ Restaurant Segmentation using Unsupervised Learning

This project uses unsupervised machine learning to segment restaurants from a Zomato dataset, providing a comprehensive analysis of their characteristics. By clustering restaurants based on their operational and service features, the goal is to uncover meaningful patterns and derive actionable insights for business strategy and targeted marketing.

📊 Project Overview
Dataset: A Zomato restaurant metadata dataset sourced from Kaggle.
Techniques Used: The project demonstrates proficiency in a full data science workflow, from data cleaning to model interpretation. Key techniques include:
Data preprocessing & feature scaling
Geo-spatial clustering with DBSCAN
Feature-based clustering with K-Means
Dimensionality reduction with PCA for visualization
In-depth cluster profiling and interpretation
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## 🚀 Steps Performed
Data Preprocessing: Initial steps involved loading the data, handling missing values in the Cuisines column, and cleaning categorical features like Has Online delivery by converting them into a numerical format.
Exploratory Data Analysis (EDA): A detailed EDA was conducted to understand the distribution of countries (India has the most data), the range of ratings, and the most popular cuisines.
Geo-spatial Clustering: The DBSCAN algorithm was applied to Latitude and Longitude data. To ensure accuracy for geographical points, the Haversine distance metric was used, which correctly accounts for the Earth's curvature.
Feature-Based Clustering: K-Means clustering was performed on the standardized feature data. The optimal number of clusters (k=10) was determined using both the Elbow Method and Silhouette Score, ensuring a robust model.
Dimensionality Reduction: PCA was used to reduce the 7 features down to 2 principal components. This was done to create a 2D plot, making it possible to visualize the clusters and understand their separation in the feature space.
Cluster Profiling and Interpretation: The final and most crucial step involved profiling each of the 10 K-Means clusters by analyzing the mean values of their features. Each cluster was given a descriptive, business-oriented name, transforming the data into actionable insights.

## 🛠️ How to Run
1. Clone the repo  
   `git clone https://github.com/your-username/zomato-clustering.git`
2. Install dependencies  
   `pip install -r requirements.txt`
3. Open the notebook  
   `jupyter notebook Zomato_Clustering.ipynb`

> This project demonstrates how unsupervised ML can uncover meaningful patterns in real-world restaurant data without labels.


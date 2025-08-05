# 🍽️ Zomato Restaurant Clustering using Unsupervised Learning

This project applies unsupervised machine learning techniques to cluster restaurants from the Zomato dataset based on their cost, rating, popularity, and service features. The goal is to uncover patterns among restaurants using real-world data and visualize distinct groupings without predefined labels.

## 📊 Project Overview

- **Dataset**: Zomato restaurant metadata (from Kaggle)
- **Techniques Used**:
  - Data preprocessing & feature scaling
  - Dimensionality reduction with **PCA**
  - Clustering with **KMeans** and **DBSCAN**
  - Cluster profiling and visualization
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## 🧠 Features Used for Clustering
- Average Cost for Two
- Price Range
- Aggregate Rating
- Votes
- Has Table Booking (Yes/No)
- Has Online Delivery (Yes/No)
- Is Delivering Now (Yes/No)

## 🚀 Steps Performed
1. Data cleaning and preprocessing
2. Feature selection and scaling with `StandardScaler`
3. Dimensionality reduction using PCA (for plotting)
4. Unsupervised clustering using:
   - **KMeans** (with optimal `k` chosen via Silhouette Score & Elbow Method)
   - **DBSCAN** (density-based clustering with outlier detection)
5. Visualization of clusters using PCA components
6. Cluster profiling for business insights

## 📷 Visual Outputs
- Elbow curve to choose best `k`
- Silhouette score plot
- PCA-based cluster scatter plots

## 📁 Files Included
- `Zomato_Clustering.ipynb` – Main Jupyter notebook with full analysis
- `zomato_clustered.csv` – Output data with cluster labels
- `images/` – Optional folder for screenshots or plots

## 🛠️ How to Run
1. Clone the repo  
   `git clone https://github.com/your-username/zomato-clustering.git`
2. Install dependencies  
   `pip install -r requirements.txt`
3. Open the notebook  
   `jupyter notebook Zomato_Clustering.ipynb`

## 🌐 Optional Deployment
You can deploy this notebook as an interactive app using [Streamlit](https://streamlit.io/) to allow users to explore clusters dynamically.

## 📌 Key Insights
- KMeans successfully identified high-rated budget restaurants, premium dine-in groups, and active online delivery clusters.
- DBSCAN detected outlier restaurants and organically grouped core service types.
- PCA helped reduce complexity while preserving structure for visualization.

> This project demonstrates how unsupervised ML can uncover meaningful patterns in real-world restaurant data without labels.


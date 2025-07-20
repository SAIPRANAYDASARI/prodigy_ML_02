# prodigy_ML_02
# ProdigyInfoTech_ML_02
# 🧠 Task-02: Customer Segmentation with KMeans Clustering

This project is part of my Machine Learning Internship at Prodigy InfoTech.

---

## ✅ Objective
Segment customers into meaningful groups based on the following features:
- Age
- Annual Income
- Spending Score

The objective is to identify customer segments that help businesses understand purchasing behavior and target customers more effectively.

---

## 📁 Files in this Repo
- `kmeans_customer_segmentation.ipynb` — Complete Jupyter Notebook containing:
  - Data preprocessing and cleaning
  - KMeans clustering with optimal K determined using the Elbow Method
  - 2D and 3D cluster visualization
  - Cluster profile summaries

- `clustered_customers.csv` — Cleaned data with assigned cluster labels  
- `cluster_profiles_summary.csv` — Summary of cluster profiles with averages  

---

## 📊 Cluster Profiles (Sample Output)

| Cluster | Average Age | Average Annual Income | Average Spending Score |
|---------|-------------|------------------------|------------------------|
| 0       | 56.7        | 54.07                  | 48.66                  |
| 1       | 32.86       | 78.55                  | 82.17                  |
| 2       | 44.00       | 90.13                  | 17.93                  |
| 3       | 21.00       | 63.23                  | 40.68                  |
| 4       | 25.27       | 25.73                  | 79.36                  |
| 5       | 34.09       | 23.55                  | 25.45                  |
| 6       | 33.41       | 53.14                  | 50.32                  |
| 7       | 32.20       | 109.70                 | 82.00                  |
| 8       | 55.20       | 26.90                  | 13.00                  |

### 🔍 Example Observations:
- Cluster 7: Younger customers with high income and high spending — premium target segment.
- Cluster 2: Middle-aged with high income but low spending — focus area for improving engagement.
- Cluster 4: Younger, low-income but high-spending — potential value seekers.

---

## 📌 Key Techniques Used
- 📊 **KMeans Clustering** using scikit-learn
- 📏 **Feature Scaling** with StandardScaler
- 📉 **Elbow Method** for optimal K determination
- 📊 **Data Visualization** with Matplotlib and Seaborn (2D and 3D)
- 🖥️ **Cluster Profiling** for business insights

---

## 🛠 Tools & Libraries
- Python (Jupyter Notebook)
- Pandas, NumPy for data manipulation
- Scikit-learn for machine learning
- Seaborn, Matplotlib for plotting (2D & 3D visualizations)

---

## 📬 Connect with Me
- 🔗 [LinkedIn](https://www.linkedin.com/in/sai-pranay-dasari-161311327/)
- 📧 [Email](mailto:saipranaydasari2006@gmail.com)

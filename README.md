
# 🚦 UK Traffic Data Analysis using Big Data and Distributed Computing (DSA7002)

Welcome to the repository for my **DSA7002 - Big Data Technologies** coursework at Cardiff Metropolitan University (2024–25 Semester 2). This project focuses on applying distributed computing principles with Apache Spark to explore and model UK traffic data from 2000 to 2023.

---

## 📌 Overview

This project explores the scalability, performance, and analytics capabilities of distributed systems. The dataset, sourced from the UK Department for Transport (DfT), includes traffic volume and vehicle type data across regions and years. The key components of the analysis include:

1. Data preparation and cleansing using PySpark.
2. Exploratory data analysis (EDA) with both DataFrame and RDD transformations.
3. Unsupervised learning (K-Means clustering).
4. Supervised learning (Decision Tree and Random Forest classifiers).

---

## 📁 Project Structure

```
📦 UK-Traffic-Big-Data-Analysis/
│
├── 📄 st20310829_DSA7002_PRAC1.ipynb       # Main Jupyter Notebook with all analysis
├── 📄 st20310829_DSA7002_PRAC1_REPORT.pdf  # Final project report
└── 📄 README.md                            # This file
```

---

## 🧠 Key Tasks Covered

### 🔹 Task 1: Data Preparation
- Data loaded and validated using PySpark.
- Missing value imputation and outlier removal.
- Z-score normalization applied for balanced clustering.

### 🔹 Task 2: Exploratory Data Analysis
- Applied aggregation and filtering using Spark DataFrames and RDDs.
- Uncovered trends like reduced traffic during the 2008 crisis and COVID-19.
- Visualizations exported for Matplotlib/Seaborn rendering.

### 🔹 Task 3: Clustering
- K-Means clustering using PySpark MLlib.
- Optimal cluster number selected using the Elbow Method and Silhouette Score.
- PCA used to reduce dimensionality for interpretability.

### 🔹 Task 4: Supervised Learning
- Trained Decision Tree and Random Forest models to predict cluster membership.
- Random Forest achieved higher performance; Decision Tree was more interpretable.
- Evaluation via accuracy, F1-score, and confusion matrix.

---

## ⚙️ Tools & Technologies Used

- **Apache Spark (PySpark)**: Distributed data processing and machine learning
- **Python Libraries**: Pandas, Matplotlib, Seaborn (for external visualizations)
- **MLlib**: Clustering (K-Means), Classification (Decision Tree, Random Forest)

---

## 🧩 Skills Demonstrated

- Distributed data preprocessing and analysis
- Efficient use of Spark transformations (RDD vs DataFrame)
- Cluster modeling and pseudo-labeling for ML
- Balancing trade-offs between interpretability and accuracy in model selection
- Critical analysis of tool performance in a big data context

---

## 👨‍🎓 Author

**Name:** Bapti Niloy Sarkar  
**Student ID:** st20310829  
**University:** Cardiff Metropolitan University  
**Module:** DSA7002 - Big Data Technologies  

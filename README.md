# Customer Segmentation Project

This project segments customers based on their demographics, purchasing behavior, and response to marketing campaigns, using unsupervised clustering techniques. The goal is to identify distinct customer groups that can inform targeted marketing strategies and personalized engagement.

---

## 🔑 Key Features

- Data preprocessing and feature engineering, including handling of missing values and outliers across demographic and behavioural fields
- Principal Component Analysis (PCA) for dimensionality reduction, condensing 29 original features into 2–3 principal components for tractable clustering and visualization
- Clustering techniques compared across **K-Means, Hierarchical Clustering, and Gaussian Mixture Models (GMM)**, including a modified K-Means variant using cosine similarity
- Evaluation of clustering performance using Silhouette Score to select the best-performing method

---

## 📊 Dataset

- **Size:** 2,240 rows × 29 columns
- **Features:** customer demographics (age, income, education, marital status, etc.), purchasing behavior (spending across product categories, purchase channels), and response to marketing campaigns
- **Preprocessing:** addressed missing values and outliers prior to modelling to ensure clustering wasn't distorted by noisy or incomplete records

---

## 🏆 Results

- Reduced the original 29 features to **2–3 principal components** via PCA while retaining the structure needed to separate customer groups
- Compared K-Means, Hierarchical Clustering, and GMM; the best configuration produced **3 distinct customer segments** with a **Silhouette Score of 0.71**, indicating well-separated, cohesive clusters
- The resulting segments support downstream use cases like targeted marketing and campaign personalization

---

## 📁 Project Structure

```
Customer_Segmentation/
├── data/         # Dataset used in the project
├── notebooks/    # Jupyter notebooks: preprocessing, PCA, and clustering
└── README.md     # Project overview, setup instructions, and usage guide
```

---

## ⚙️ Dependencies

- Python 3.x
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn

Install the Python dependencies with:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## Author

**Manya Gupta**: [@manyagupta-21](https://github.com/manyagupta-21)


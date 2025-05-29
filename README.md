# 🧠 Wholesale Customer Clustering - Unsupervised Learning Case Study

This project demonstrates unsupervised machine learning techniques to explore and cluster customer segments using the **Wholesale Customers Dataset**. Various clustering models like **K-Means**, **Agglomerative Clustering**, and **DBSCAN** are applied, and **PCA** is used for dimensionality reduction and visualization.

---

## 📁 Dataset

The dataset used is the [Wholesale customers data.csv](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers), which contains the annual spending in monetary units (m.u.) on diverse product categories for clients of a wholesale distributor.

| Feature            | Description                              |
|--------------------|------------------------------------------|
| Fresh              | Annual spending on fresh products        |
| Milk               | Annual spending on milk products         |
| Grocery            | Annual spending on grocery products      |
| Frozen             | Annual spending on frozen products       |
| Detergents_Paper   | Annual spending on detergents & paper    |
| Delicassen         | Annual spending on delicatessen items    |

> Note: Columns `Channel` and `Region` were dropped during preprocessing.

---

## 📊 Techniques Used

### 🔧 Preprocessing
- Handled null values
- Removed non-informative features (`Channel`, `Region`)
- Standardized data using `StandardScaler`

### 🔍 Clustering Models
- **K-Means Clustering**
  - Used Elbow Method to determine the optimal number of clusters
- **Agglomerative Clustering**
  - Built dendrograms to decide cluster count
- **DBSCAN**
  - Density-Based Spatial Clustering

### 📉 Dimensionality Reduction
- **PCA (Principal Component Analysis)**
  - Reduced data to 2 principal components
  - Used for visualizing clustering results

---

## 📈 Visualizations

- Elbow Curve for K-Means
- Dendrogram for Hierarchical Clustering
- PCA scatter plots for all clustering methods

---

## 🛠 Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Wholesale-Customer-Clustering.git
   cd Wholesale-Customer-Clustering

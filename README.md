# customer-segmentation-kmeans 
"Customer Segmentation Analysis using K-Means Clustering"

This project performs **unsupervised customer segmentation** on the **Mall Customers dataset**, identifying distinct customer groups based on their demographic information and spending behavior.

Developed as part of my **Machine Learning internship**, this project demonstrates proficiency in **K-Means clustering**, cluster evaluation using **Elbow Method** and **Silhouette Score**, and **visualization of customer segments**.

# Project Goal

To segment customers into distinct groups using **K-Means clustering**, analyze their characteristics, and visualize the separation between clusters.

# Project Workflow

### 1. Dataset Acquisition and Preparation
- Loaded the **Mall Customers dataset**.  
- Performed data cleaning and preprocessing.  
- Selected relevant **numerical features** such as:
  - Annual Income  
  - Spending Score  
  - (Optionally) Age and Gender (encoded numerically if used).  

### 2. K-Means Clustering Implementation and Optimization
- Applied the **K-Means** algorithm for clustering.  
- Determined the optimal number of clusters (`k`) using:
  - **Elbow Method:** Based on inertia (sum of squared distances).  
  - **Silhouette Score:** Based on cluster separation quality.  

### 3. Cluster Analysis and Visualization
- Trained the final **K-Means model** using the optimal `k`.  
- Assigned each customer to a cluster.  
- Visualized clusters using:
  - **2D Scatter Plot** (Annual Income vs. Spending Score).  
  - **3D Plot** (optional, e.g., Age, Income, and Spending Score).  

# Tools and Libraries
- **Python 3.x**
- **Pandas** – for data manipulation  
- **NumPy** – for numerical operations  
- **Scikit-learn** – for clustering (`KMeans`, `silhouette_score`)  
- **Matplotlib** – for visualization  
- **Seaborn** – for enhanced, color-coded cluster plots  

# How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-segmentation-kmeans.git

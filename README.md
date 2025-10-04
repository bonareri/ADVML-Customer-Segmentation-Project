## Customer Segmentation Project  

### Project Overview  

This project focuses on performing **customer segmentation** using **clustering algorithms** to identify groups of customers with similar characteristics and purchasing behaviors.  

Customer segmentation is a key marketing strategy that enables businesses to tailor their marketing efforts, improve customer retention, and enhance product offerings. By leveraging machine learning techniques, this project provides data-driven insights into how different types of customers interact with a business.  

The analysis combines both **traditional** and **advanced clustering methods** — including **K-Means**, **Hierarchical Clustering**, **DBSCAN**, and **Gaussian Mixture Models (GMM)** — to uncover meaningful patterns within the data.  

### Project Objectives  

The main goals of this project were to:  

- Understand the characteristics and behavior of customers through **exploratory data analysis (EDA)**.  
- Group customers into distinct segments using clustering algorithms.  
- Compare and evaluate the performance of traditional and advanced clustering models.  
- Derive actionable business insights from the identified clusters.  
- Visualize clusters for easier interpretation and communication of findings.  

### Dataset  

The dataset used in this project contains various customer attributes, including:  

- **Demographic information:** Age, Gender, Location, and Income.  
- **Behavioral data:** Purchase Frequency, Average Spending, Total Revenue, and Recency of Purchases.  

Before modeling, the dataset underwent extensive **data cleaning and preprocessing**, which included:  

- Handling missing values and outliers.  
- Encoding categorical variables into numerical form.  
- Normalizing numerical features to improve clustering performance.  

### Methodology  

### 1. Data Exploration and Visualization  
I began with an in-depth exploratory data analysis (EDA) to understand the underlying structure of the dataset. This included:  
- Visualizing distributions of key features such as Age, Income, and Spending.  
- Examining relationships between features using correlation heatmaps and scatterplots.  
- Identifying potential patterns or anomalies in customer spending behavior.  

### 2. Feature Selection and Scaling  
Relevant features were selected for clustering, and all numerical variables were scaled using **StandardScaler** to ensure uniformity across features.  

### 3. Clustering Models  
Multiple clustering algorithms were applied to capture different perspectives of customer grouping:  
- **K-Means Clustering:** Used as the baseline model to create well-separated clusters.  
- **Hierarchical Clustering:** Provided a visual dendrogram to explore cluster merging patterns.  
- **DBSCAN:** Detected density-based clusters and outliers that other methods might miss.  
- **Gaussian Mixture Models (GMM):** Offered probabilistic cluster assignments, giving a more flexible segmentation approach.  

### 4. Model Evaluation  
To determine the best model and number of clusters, I used:  
- **Elbow Method** — for identifying the optimal number of K-Means clusters.  
- **Silhouette Score** — to measure cluster cohesion and separation.  
- **Davies-Bouldin Index** — as an additional cluster quality metric.  

### 5. Interpretation and Visualization  
Each cluster was analyzed to uncover distinguishing characteristics, such as:  
- Average age and income.  
- Spending frequency and purchase behavior.  
- Responsiveness to promotions or discounts.  

Clusters were visualized using **2D scatter plots**, **pairplots**, and **PCA (Principal Component Analysis)** for dimensionality reduction.  

### Results & Insights  

The clustering analysis revealed several meaningful customer segments. Examples include:  
- **High-Value Customers:** High income and frequent purchases.  
- **Budget-Conscious Shoppers:** Low to moderate income, responsive to discounts.  
- **Occasional Buyers:** Irregular purchasing behavior with low engagement.  
- **Potential Loyalists:** Moderate spenders with consistent purchasing patterns.  

These insights can guide marketing teams to design **targeted campaigns**, **personalized offers**, and **customer retention strategies** based on each group’s characteristics.  

### Technologies Used  

- **Programming Language:** Python  
- **Libraries:**  
  - `pandas`, `numpy` — Data manipulation and preprocessing  
  - `matplotlib`, `seaborn`, `plotly` — Data visualization  
  - `scikit-learn` — Clustering models and evaluation metrics  
  - `scipy` — Hierarchical clustering analysis  

### Evaluation Metrics  

- **Elbow Method (WCSS):** Determined optimal number of clusters.  
- **Silhouette Score:** Evaluated separation and consistency within clusters.  
- **Davies-Bouldin Index:** Measured similarity between clusters (lower is better).  

The **K-Means** and **GMM** models produced the most interpretable clusters with high silhouette scores, while **DBSCAN** was effective in identifying outliers and non-linear groupings.  


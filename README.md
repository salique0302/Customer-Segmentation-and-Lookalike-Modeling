### **Customer Segmentation and Lookalike Modeling Project**

#### **Project Overview**
This project focuses on understanding customer behavior through clustering and lookalike modeling. It involves three key tasks:
1. Exploratory Data Analysis (EDA) and Business Insights.
2. Lookalike Model to identify similar customers.
3. Customer Segmentation using clustering techniques.

The goal is to extract meaningful insights, segment customers effectively, and create a lookalike model for targeted recommendations.


#### **Tasks and Outcomes**

### **Task 1: Exploratory Data Analysis (EDA)**
- Conducted a detailed EDA on customer and transaction data.
- Key insights include:
  - **Regional Revenue Contribution**: South America contributes the highest revenue, followed by Europe, North America, and Asia.
  - **Top Products**: Identified 5 best-selling products and their dominant regions.
  - **Category Contributions**: Electronics, Books, Home Decor, and Clothing contribute almost equally to revenue.
  - **Signup and Revenue Trends**: Maximum signups occurred in September and November 2024, but November had the lowest revenue, indicating potential conversion issues.
  - **Monthly Category Trends**: Identified top-performing categories for each month.
- Visualizations such as bar charts, stacked bar graphs, and pie charts were used to highlight these insights.


### **Task 2: Lookalike Model**
- Built a lookalike model to identify customers similar to a given user based on profile and transaction data.
- Methods:
  - **Cosine Similarity**
  - **Euclidean Similarity**
  - **Manhattan Similarity**
- Validation:
  - Evaluated methods using clustering metrics and selected **Cosine Similarity** for final recommendations.
- Deliverables:
  - Generated a `Lookalike.csv` file mapping the first 20 customers (C0001-C0020) to their top 3 lookalikes with similarity scores.

### **Task 3: Customer Segmentation**
- Performed customer segmentation using clustering techniques.
- Clustering Methods:
  - KMeans
  - DBSCAN
  - Hierarchical Clustering
- Evaluation:
  - Best Method: **Hierarchical Clustering** with 7 clusters.
  - **Davies-Bouldin Index**: 0.9569
  - **Silhouette Score**: 0.3707
  - **Calinski-Harabasz Index**: 77.566
- Visualizations:
  - Dendrogram: Displayed hierarchical relationships and the threshold for 7 clusters.
  - PCA: Plotted customer clusters in a 2D space for easy interpretation.

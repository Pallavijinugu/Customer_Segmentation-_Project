# Customer_Segmentation-_Project
# Customer Segmentation Using K-Means Clustering

## Project Overview

Customer Segmentation is the process of dividing customers into groups based on their purchasing behavior and demographic characteristics. This project uses the K-Means Clustering algorithm to identify different customer segments and analyze their characteristics.

The goal is to help businesses understand their customers better and create targeted marketing strategies.

---

## Objectives

- Perform customer segmentation using Machine Learning.
- Analyze customer purchasing behavior.
- Identify high-value and low-value customer groups.
- Visualize customer segments using graphs.
- Generate business insights from customer data.

---

## Dataset

Dataset Used: Mall Customers Dataset

### Features

| Column Name | Description |
|------------|-------------|
| CustomerID | Unique customer identifier |
| Gender | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousand dollars |
| Spending Score (1-100) | Customer spending behavior score |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Machine Learning Algorithm

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm used to group similar data points into clusters.

Steps:
1. Select the number of clusters (K).
2. Initialize cluster centroids.
3. Assign data points to the nearest centroid.
4. Recalculate centroids.
5. Repeat until convergence.

---

## Project Workflow

### Step 1: Data Collection
- Load customer dataset.

### Step 2: Data Exploration
- Check dataset structure.
- Handle missing values.
- Analyze statistical information.

### Step 3: Feature Selection
Selected Features:
- Annual Income (k$)
- Spending Score (1-100)

### Step 4: Elbow Method
Used to determine the optimal number of clusters.

### Step 5: K-Means Clustering
Applied K-Means algorithm to segment customers.

### Step 6: Data Visualization
Visualized customer clusters using scatter plots.

### Step 7: Customer Analysis
Analyzed characteristics of each customer segment.

---

## Results

The algorithm divided customers into multiple groups based on income and spending behavior.

Typical segments include:

### Cluster 1
- High Income
- High Spending
- Premium Customers

### Cluster 2
- High Income
- Low Spending
- Potential Customers

### Cluster 3
- Low Income
- High Spending
- Promotional Target Customers

### Cluster 4
- Low Income
- Low Spending
- Budget Customers

### Cluster 5
- Average Income
- Average Spending
- Regular Customers

---

## Visualizations

### Elbow Method
Used to identify the optimal number of clusters.

### Customer Segmentation Scatter Plot
Shows customer groups based on income and spending score.

---

## Key Insights

- High-income customers are not always high spenders.
- Premium customers contribute significantly to revenue.
- Marketing campaigns can target specific customer groups.
- Customer segmentation helps improve business decision-making.

---

## Future Improvements

- Use additional customer features.
- Apply hierarchical clustering.
- Create an interactive Power BI dashboard.
- Deploy the model as a web application.

---

## How to Run the Project

### Clone Repository

```bash
git clone <repository-link>
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
customer_segmentation.ipynb
```

and run all cells.

---

## Project Structure

```text
Customer-Segmentation/
│
├── data/
│   └── Mall_Customers.csv
│
├── notebook/
│   └── customer_segmentation.ipynb
│
├── images/
│   ├── elbow_method.png
│   └── customer_segments.png
│
├── Customer_Segments.csv
│
└── README.md
```

---

## Conclusion

This project successfully demonstrates customer segmentation using K-Means Clustering. The identified customer groups can help businesses understand customer behavior, improve marketing strategies, and increase customer satisfaction and revenue.

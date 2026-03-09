# Customer Segmentation & Spending Behavior Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue)
![ML](https://img.shields.io/badge/MachineLearning-ScikitLearn-orange)

Data analysis project exploring customer demographics and spending patterns to identify meaningful customer segments and key drivers of purchasing behavior.

This project demonstrates a complete **data analyst workflow**, including data cleaning, exploratory data analysis (EDA), statistical exploration, clustering, and business insight generation.

---

# Business Question

Which types of customers generate the highest spending and how can they be segmented to support targeted marketing strategies?

Key objectives:

- Identify factors influencing customer spending behavior
- Explore relationships between income, age, and spending
- Detect meaningful customer segments
- Generate insights that could support marketing decisions

---

# Dataset

Customer demographic and spending data.

Main variables:

| Variable | Description |
|--------|-------------|
| CustomerID | Unique customer identifier |
| Gender | Customer gender |
| Age | Customer age |
| Annual Income | Annual income (k$) |
| Spending Score | Spending index assigned by the store |

Dataset source:  
Public dataset for customer segmentation analysis.

---

# Analytical Workflow

## 1. Data Loading

- Imported dataset
- Inspected structure and column types
- Verified dataset integrity

---

## 2. Data Cleaning

- Checked for missing values
- Verified data types
- Inspected dataset structure
- Prepared variables for analysis

---

## 3. Exploratory Data Analysis (EDA)

Explored distributions and relationships between variables.

Key analyses included:

- Age distribution
- Income distribution
- Spending score distribution
- Correlation analysis
- Income vs spending patterns

Visualizations used:

- Histograms
- Scatter plots
- Box plots
- Correlation heatmap


---

## 4. Customer Segmentation

Clustering techniques were used to identify customer groups based on spending behavior and income.

Approach:

- Feature selection
- Feature scaling
- Applying K-Means clustering
- Interpreting resulting segments

Example segments:

| Segment | Description |
|-------|-------------|
| High income / high spending | High-value customers |
| High income / low spending | Potential marketing targets |
| Low income / high spending | Impulse buyers |
| Low income / low spending | Low-value segment |

---

## Cluster Profiling

| Cluster | Income Level | Spending Behavior | Interpretation |
|-------|-------------|-------------|-------------|
| 0 | High | High | High Value Customers |
| 1 | High | Low | Careful Spenders |
| 2 | Low | High | Potential Loyalists |
| 3 | Low | Low | Low Engagement |

---

## Visualizations

### Elbow Method

![Elbow](images/elbow_method.png)

### Customer Segments

![Clusters](images/cluster_plot.png)

### Age Distribution

![Age](images/age_distribution.png)

---

## Business Insights

Most clustering projects stop at visualization.  
In this project I go one step further — translating clusters into **business actions**.

After performing customer segmentation, each cluster is analyzed to understand:

- spending behavior
- purchase frequency
- product preferences
- marketing potential

### Example Segment Interpretation

| Segment | Description | Business Strategy |
|-------|-------------|----------------|
| High Value Customers | High spending and frequent purchases | Loyalty programs, VIP offers |
| Potential Loyalists | Medium spending but growing activity | Targeted promotions, bundles |
| Occasional Buyers | Low frequency and moderate spending | Retargeting campaigns |
| At-Risk Customers | Previously active but declining | Win-back campaigns |

### Why This Matters

Data science is not only about models — it’s about **decision making**.

By translating clusters into business strategies, this project demonstrates:

- analytical thinking
- product mindset
- ability to communicate results to stakeholders

This approach is commonly expected from **Middle+ Data Scientists**.

# Tools & Technologies

Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Scikit-learn  
Jupyter Notebook  

---
# Project Structure

data/
  └── dataset.csv
notebooks/
  ├── eda.ipynb
│ └── customer_segmentation.ipynb
visualizations/
  └── plots/
README.md
---

# Key Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Data visualization
- Customer segmentation
- Clustering techniques
- Analytical storytelling
- Translating data into business insights

---

# Author

**Larysa Yanushchyk**

GitHub:  https://github.com/BuhaAutilla

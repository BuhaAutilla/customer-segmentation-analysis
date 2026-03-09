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

# Key Insights

1. Spending behavior does not always correlate directly with income.

2. Certain age groups demonstrate higher spending activity.

3. Distinct customer segments can be identified using clustering methods.

4. High-income customers with low spending represent a potential growth opportunity.

---

# Business Recommendations

Based on the analysis:

- High income / low spending customers could be targeted with promotional campaigns.
- Younger high-spending customers may benefit from loyalty programs.
- Customer segmentation could support personalized marketing strategies.

---

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

customer-segmentation-analysis
│
├── data
│ └── dataset.csv
│
├── notebooks
│ ├── eda.ipynb
│ └── customer_segmentation.ipynb
│
├── visualizations
│ └── plots
│
└── README.md


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

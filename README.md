
# Customer Segmentation using K-Means Clustering

## Project Overview

This project performs Customer Segmentation using Machine Learning (K-Means Clustering). The objective is to group customers based on their demographic information and purchasing behavior, enabling businesses to create targeted marketing strategies and improve customer engagement.

The project follows a complete Data Science workflow including data cleaning, exploratory data analysis (EDA), feature engineering, feature scaling, dimensionality reduction using PCA, clustering, visualization, and business insights.

---

## Dataset

Dataset: Marketing Campaign Dataset

Number of Records: 2240

Features include:

- Income
- Age
- Education
- Marital Status
- Children
- Customer Since Date
- Purchase Amounts
- Campaign Response
- Product Spending

---

## Project Workflow

- Import Libraries
- Load Dataset
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Scaling
- Principal Component Analysis (PCA)
- Elbow Method
- K-Means Clustering
- Cluster Visualization
- Cluster Analysis
- Business Insights

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Exploratory Data Analysis

The following analyses were performed:

- Age Distribution
- Income Distribution
- Total Spending Distribution
- Education Analysis
- Marital Status Analysis
- Income vs Spending
- Age vs Spending
- Income by Education
- Correlation Heatmap

---

## Feature Engineering

New features created:

- Age
- Children
- Customer_Years
- Total_Spending

Selected features for clustering:

- Income
- Age
- Children
- Customer_Years
- Total_Spending

---

## Machine Learning

The dataset was standardized using StandardScaler.

PCA was applied to reduce dimensionality for visualization.

The Elbow Method was used to determine the optimal number of clusters.

K-Means Clustering grouped customers into meaningful customer segments.

---

## Business Insights

- High-income customers spend significantly more.
- Customer spending strongly depends on income.
- Distinct customer groups were identified using K-Means.
- Businesses can target premium customers with loyalty programs.
- Medium-value customers can receive personalized recommendations.
- Low-value customers can be targeted through promotional offers.
- Customer segmentation helps improve marketing efficiency.

---

## Results

The project successfully segments customers into meaningful groups using Machine Learning.

The generated customer segments can help businesses:

- Improve customer retention
- Increase sales
- Personalize marketing campaigns
- Identify high-value customers
- Optimize promotional strategies

---

## Project Structure

```
Customer-Segmentation/
│
├── marketing_campaign.csv
├── Customer_Segmentation.ipynb
├── Customer_Segmentation_Report.pdf
├── README.md
└── requirements.txt
```

---

## Author

GitHub:
https://github.com/hemanth350

---

## Future Improvements

- Interactive Power BI Dashboard
- Streamlit Web Application
- Customer Lifetime Value Prediction
- Recommendation System
- Deep Learning-based Customer Segmentation

---

## License

This project is for educational and portfolio purposes.

Mall Customer Segmentation

This project applies data cleaning, preprocessing, and customer segmentation techniques to a retail dataset of mall customers. The goal is to understand customer spending behavior, group them into meaningful clusters, and generate insights that can guide targeted marketing strategies.

📂 Project Structure
Mall Customer Segmentation Data.ipynb → Jupyter Notebook with end-to-end analysis
Mall_Customers(1).xls → Original dataset
Mall_Customers_cleaned.csv → Cleaned dataset ready for analysis

🧹 Data Cleaning & Preprocessing
Standardized column names and removed duplicates
Handled missing values using median (numeric) and mode (categorical)
Normalized categorical values (e.g., gender)
Converted numeric-like text columns into numeric types

📊 Analysis Performed
Exploratory Data Analysis (EDA): Univariate & bivariate visualizations of income, spending score, and age distribution
Segmentation: Applied clustering algorithms (e.g., K-Means) to group customers based on income and spending behavior
Visualization: Used scatter plots, heatmaps, and cluster charts to highlight patterns

💡 Key Insights
Customers naturally group into distinct segments based on income vs. spending score
Identified high-value clusters (e.g., high income & high spenders) suitable for loyalty programs
Found budget-conscious groups (low income & low spenders) requiring different marketing strategies

🚀 Tech Stack
Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
Jupyter Notebook for reproducible analysis

📈 Applications
Targeted marketing campaigns
Personalized promotions for different customer groups
Strategic decision-making in retail and e-commerce

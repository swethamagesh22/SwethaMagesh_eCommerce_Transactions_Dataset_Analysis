# 
eCommerce_Transactions_Dataset_Analysis

## Description
This repository involves analyzing an eCommerce transactions dataset to derive actionable business insights, build a lookalike model, and perform customer segmentation using clustering techniques. The project demonstrates data analysis, visualization, and machine learning skills.

## Dataset
The analysis is based on three CSV files:
- **Customers.csv**: Contains customer information, including unique IDs, names, regions, and signup dates.
- **Products.csv**: Contains product details, including unique IDs, names, categories, and prices.
- **Transactions.csv**: Contains transaction records, including transaction IDs, customer IDs, product IDs, transaction dates, quantities, and total values.

## Tasks
The project is divided into four main tasks:

1. **Exploratory Data Analysis (EDA)**:
   - Analyze customer demographics, product categories, and sales trends.
   - Visualize key metrics using bar plots, line graphs, and histograms.
   - Generate a comprehensive report summarizing the findings.

2. **Business Insights**:
   - Calculate key metrics such as average spend per customer, total revenue, and product performance.
   - Generate actionable insights based on the analysis.
   - Save insights in a PDF report for easy reference.

3. **Lookalike Model**:
   - Create a model to identify similar customers based on their transaction history and profile.
   - Use RFM (Recency, Frequency, Monetary) analysis and category preferences for feature engineering.
   - Generate a CSV file containing the top 3 lookalikes for the first 20 customers.

4. **Customer Segmentation**:
   - Perform clustering to segment customers into distinct groups.
   - Use K-means clustering and determine the optimal number of clusters.
   - Visualize the clusters and generate a report detailing cluster characteristics.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- FPDF (for PDF generation)

# Customer Segmentation Analysis

## Objective
The objective of this project is to segment customers based on their purchasing behavior using RFM (Recency, Frequency, Monetary) analysis and K-Means clustering.

## Dataset
The analysis uses the Online Retail transactional dataset.

Dataset Source:
UCI Machine Learning Repository – Online Retail Dataset

The dataset contains transactional information such as Invoice Number, Product Code, Quantity, Invoice Date, Unit Price, Customer ID, and Country.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Loaded the Online Retail dataset.
2. Inspected the dataset structure and missing values.
3. Cleaned the data by removing missing Customer IDs, cancelled transactions, and invalid quantities/prices.
4. Created the TotalAmount feature.
5. Calculated RFM metrics for each customer.
6. Applied log transformation and standardization.
7. Evaluated different K values using the Silhouette Score and Elbow Method.
8. Applied K-Means clustering.
9. Created meaningful customer segments.
10. Analyzed customer segments using visualizations.
11. Generated business insights and recommendations.

## RFM Analysis

### Recency
Number of days since the customer's most recent purchase.

### Frequency
Number of unique invoices/purchases made by the customer.

### Monetary
Total amount spent by the customer.

## Customer Segments

### At Risk / Low Value
These customers have higher recency, lower purchase frequency, and lower spending.

### High Value / Loyal
These customers have lower recency, higher purchase frequency, and higher spending.

## Business Recommendations
- Retain High Value / Loyal customers through loyalty rewards and personalized offers.
- Re-engage At Risk / Low Value customers using targeted campaigns and special offers.
- Use customer segments to support personalized marketing strategies.

## Output Files
- `customer_segments.csv`
- `segment_summary.csv`
- `customer_segmentation.ipynb`

## Conclusion
RFM analysis combined with K-Means clustering helps identify different customer behavior patterns. These segments can help businesses design more targeted customer retention and re-engagement strategies.
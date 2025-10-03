# Myntra Customer Segmentation

## Project Overview
This project performs **customer segmentation** for a fashion e-commerce platform similar to Myntra using the **Online Retail II dataset** from the UCI Machine Learning Repository. The goal is to identify distinct customer groups based on purchasing behavior using **RFM analysis (Recency, Frequency, Monetary)** and **KMeans clustering**.

## Features
- **Recency**: How recently a customer made a purchase.
- **Frequency**: How often a customer makes purchases.
- **Monetary**: Total spend by the customer.
- **LastPurchaseMonth**: Month of last purchase (for seasonal analysis).
- **LastPurchaseQuarter**: Quarter of last purchase.
- **PreferredCategory**: Simulated product category preference.
- **Cluster**: KMeans cluster assignment.

## Libraries Used
- `pandas` for data manipulation
- `numpy` for numerical computations
- `matplotlib` and `seaborn` for visualizations
- `scikit-learn` for scaling and clustering

## Dataset
- **Online Retail II dataset** from UCI ML Repository.
- Excel file containing transaction data for customers from 2010-2012.
- Dataset link: [Online Retail II](https://archive.ics.uci.edu/ml/machine-learning-databases/00502/online_retail_II.xlsx)

## Steps
1. Load and clean the dataset (remove missing Customer IDs, negative quantities).
2. Compute RFM metrics for each customer.
3. Standardize features using `StandardScaler`.
4. Apply `KMeans` clustering to segment customers.
5. Visualize clusters using scatter plots, boxplots, violin plots, and swarm plots.
6. Provide business insights for each cluster.

## Visualizations
- **RFM Boxplots, Violin, and Swarm Plots** per cluster
- **Scatter plot of Recency vs Monetary with cluster hue**
- **Bar plot showing number of customers per cluster**

## Insights
- High-value customers can be targeted with premium collections.
- Frequent buyers can be encouraged with loyalty programs.
- Churn-risk customers can be retargeted with discounts and notifications.
- Occasional buyers can be nurtured with seasonal campaigns.

## How to Run
1. Clone the repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Run all cells sequentially.

## License
This project is licensed under the **MIT License**. See the LICENSE file for details.

## Author
Chaithanya Raj Bulla

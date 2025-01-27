Customer Segmentation and Analysis

This project involves Exploratory Data Analysis (EDA), building a Lookalike Model for customer recommendations, and applying various clustering algorithms to segment customers based on transaction behavior.

Project Files

The project consists of the following files:

Datasets

Customers.csv: Contains customer data including ID, name, region, and signup date.
Products.csv: Contains product data including ID, name, category, and price.
Transactions.csv: Contains transaction data, linking customers and products, with details on quantity, price, and total value.
EDA (Exploratory Data Analysis)
Shreyas_Peyyeti_EDA.pdf: A PDF report containing the results of the EDA process, insights derived from data, and visualizations.
Shreyas_Peyyeti_EDA.ipynb: A Jupyter notebook that performs EDA on the dataset. It includes data cleaning, feature engineering, and visualizations.
Lookalike Model
Shreyas_Peyyeti_Lookalike.csv: Contains the top 3 lookalikes for the first 20 customers (CustomerID: C0001 - C0020) based on their transaction history and profile. Each entry is in the form of a map: {cust_id: [list of <cust_id, similarity_score>]}
Shreyas_Peyyeti_Lookalike.ipynb: A Jupyter notebook that builds the Lookalike Model. It recommends similar customers by analyzing customer and product data, and outputs a CSV file with the top 3 lookalikes for each of the first 20 customers.
Clustering
Shreyas_Peyyeti_Clustering.pdf: A PDF report summarizing the clustering analysis results, including performance metrics like Silhouette Score and Davies-Bouldin Index.
Shreyas_Peyyeti_Clustering.ipynb: A Jupyter notebook that applies clustering algorithms (KMeans, DBSCAN, Spectral Clustering, Agglomerative Clustering, and GMM) to segment customers. It includes model evaluation and visualization of results.

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/SHREYASP21/Customer-Segmentation.git
Install the required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Open the Jupyter notebooks in your local environment to run and explore the analyses.

Usage
The EDA notebook performs an in-depth exploration of the datasets and visualizes customer behavior and product sales patterns.
The Lookalike Model notebook recommends customers similar to a given customer based on their transaction data and profile. The Lookalike.csv generated from this model contains the top 3 lookalikes with their similarity scores for the first 20 customers.
The Clustering notebook applies several clustering algorithms and evaluates their performance based on clustering metrics.

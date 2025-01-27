# Customer Transaction Data Analysis

## Project Overview
This project focuses on analyzing customer transactions to derive insights, build a lookalike model for customer recommendations, and perform customer segmentation using clustering techniques.

## Task 1: Exploratory Data Analysis (EDA)
### Key Findings:
- **Total Customers:** 200  
- **Total Products:** 100  
- **Total Transactions:** 1000  

### Business Insights:
1. The majority of customers are from South America, contributing significantly to revenue.
2. 'ActiveWear Smartwatch' is the best-selling product, indicating high demand.
3. Monthly revenue peaks in July 2024, suggesting seasonal demand trends.
4. Most customers spend between $2162 and $4770, with a few high-value customers.
5. The top 10% of customers contribute to nearly 19.97% of total revenue, highlighting the importance of retention strategies.

## Task 2: Lookalike Model
A Lookalike Model was developed to recommend similar customers based on profile and transaction history.

### Output Example:
```
CustomerID     Lookalikes
C0001         [('C0137', 0.9784), ('C0152', 0.9695), ('C0056', 0.9523)]
C0002         [('C0029', 0.9164), ('C0199', 0.8785), ('C0031', 0.8653)]
```

## Task 3: Customer Segmentation
Using clustering techniques, customers were grouped based on their transaction behaviors.

### Sample Output:
```
CustomerID    Cluster    PCA1    PCA2
C0001        0         -0.026   -0.089
C0002        1         -1.176   -0.811
C0003        1         -0.741    0.114
C0004        2         2.177    -0.576
```

## Repository Contents
- `Pugazharasan_A_EDA.ipynb`: Jupyter Notebook containing EDA and insights.
- `Pugazharasan_A_lookalike.ipynb`: Implementation of the Lookalike Model.
- `Pugazharasan_A_customer_segmentation.ipynb`: Clustering model and evaluation.
- `Pugazharasan_A_Lookalike.csv`: Top 3 recommended customers for each of the first 20 customers.

## How to Use
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run Jupyter notebooks to explore the analysis and models.

## Contact
For any questions, feel free to reach out!


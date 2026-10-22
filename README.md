# E-Commerce_Customer_Insights_Engine
# GetIntern Week 2 Milestone Project

### Objective
The objective of this project is to combine customer and transactional datasets and extract useful business insights using Python and Pandas.

### Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy

### Methodology
1. Created and loaded `customers.csv` and `orders.csv`.
2. Applied inner and left joins using `customer_id`.
3. Identified customers who have never placed an order.
4. Used `groupby()` and `agg()` to calculate customer spending, order counts, and average order value.
5. Segmented business metrics by city and region.
6. Constructed a Top 5 customer leaderboard based on total spend.
7. Validated the results using assertions.

### Top 5 Highest-Spending Customers

| Rank | Customer | City | Total Spend | Orders |
|---:|---|---|---:|---:|
| 1 | Kiran Reddy | Bengaluru | 23,200 | 3 |
| 2 | Asha Rao | Hyderabad | 21,600 | 3 |
| 3 | Meena Devi | Visakhapatnam | 15,700 | 3 |
| 4 | Divya Patel | Ahmedabad | 9,900 | 1 |
| 5 | Priya Nair | Chennai | 9,800 | 2 |

### Key Findings
- Total revenue is 108,100 across 20 orders.
- Overall average order value is 5,405.
- The South region has the highest revenue, at 75,800.
- Kiran Reddy is the highest-spending customer in the sample dataset.
- One registered customer has no purchases.

### Conclusion
This project demonstrates relational data joins, customer cohort filtering, and multi-dimensional KPI aggregation. These techniques can support customer segmentation, sales reporting, and data-driven business decisions.


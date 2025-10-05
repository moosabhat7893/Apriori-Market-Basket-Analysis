# Apriori-Market-Basket-Analysis
Market Basket Analysis using the Apriori algorithm to uncover hidden associations between products in a grocery dataset. Generates association rules based on support, confidence, and lift to identify potential cross-selling opportunities.


# Objective
To identify relationships between products and generate 'association rules' using metrics such as **support**, **confidence**, and **lift** — helping retailers uncover cross-selling opportunities and improve store layout or recommendations.

# Technologies / Libraries
- Python  
- pandas, numpy  
- mlxtend / apyori  
# Dataset:
[Groceries Dataset](https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset) containing transactions of items purchased by different members over time.
 

# Key Features
- Data preprocessing and transaction grouping (customer + date based)  
- Applied Apriori algorithm to find frequent itemsets  
- Generated association rules with support, confidence, and lift  
- Filtered the most significant rules for insights  
- Example: “Customers buying *yogurt* are 1.6× more likely to buy *whole milk*.”

# Results
| Left Hand Side | Right Hand Side | Support | Confidence | Lift |
|----------------|-----------------|---------|------------|------|
| rolls/buns     | whole milk      | 0.0011  | 0.21       | 1.34 |
| yogurt         | whole milk      | 0.0014  | 0.25       | 1.61 |

**Insights:**
- Customers who buy yogurt often also buy whole milk.  
- Such patterns can help design promotions and optimize shelf placements.

# Future Enhancements
- Compare Apriori vs ECLAT for efficiency and rule discovery.  
- Visualize rules using network graphs or heatmaps.  
- Build an interactive dashboard for exploring associations.



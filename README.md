#  Market Basket Analysis


##  Project Overview
This project applies **Market Basket Analysis** using the **Apriori algorithm** on the *Online Retail Dataset* from the UCI Machine Learning Repository.

The goal is to uncover **association rules** and **frequent itemsets** from transactional data to understand customer purchasing patterns and extract business insights for different market regions.

---

##  Objectives
1. **Data Preparation and Exploration**  
   - Handle missing values, outliers, and data cleaning  
   - Perform distribution and correlation analysis  
   - Manage redundant variables and transformations  

2. **Market Basket Analysis using Apriori Algorithm**  
   - Split the dataset by region (top 3 countries)  
   - Generate frequent itemsets and association rules  
   - Analyze support, confidence, and lift metrics  

3. **Business Insights**  
   - Interpret important association rules per basket  
   - Discuss their business relevance and strategic value  

---

##  Dataset
**Source:** [UCI Machine Learning Repository – Online Retail Data](https://archive.ics.uci.edu/ml/datasets/online+retail)

**Description:**  
A UK-based online retail company dataset containing transactions between **01/12/2010** and **09/12/2011**, selling unique all-occasion gifts.

| Attribute | Description |
|------------|--------------|
| InvoiceNo | Transaction ID |
| StockCode | Product code |
| Description | Product name |
| Quantity | Units purchased |
| InvoiceDate | Transaction date/time |
| UnitPrice | Price per unit (£) |
| CustomerID | Unique customer ID |
| Country | Customer country |

---

##  Technologies Used
- Python 
- Pandas
- NumPy
- Matplotlib / Seaborn
- mlxtend (for Apriori & Association Rules)
- Jupyter Notebook

---

##  Results Summary
- Top 3 baskets analyzed based on transaction volume.
- Extracted key association rules with strong support and confidence.
- Business recommendations for marketing, inventory planning, and regional promotion strategies.

---

##  Files Included
- `market_basket_analysis.ipynb` → Code notebook  
- `README.md` → Documentation file

---

##  Author
**Charith Geethaka**  
  
[cgeethaka96@gmail.com](mailto:cgeethaka96@gmail.com)  
[LinkedIn](https://www.linkedin.com/in/charith-geethaka) | [GitHub](https://github.com/CGeethaka)

---

##  License
This project is released under the [MIT License](LICENSE).

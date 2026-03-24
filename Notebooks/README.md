# Deep Ice Cream (DIC)

This project explores sales data to uncover patterns in revenue, product performance, and regional behavior, supporting data-driven decision-making.
---

## 📌 Objective
This project presents an Exploratory Data Analysis (EDA) of a simulated sales system for an ice cream business, built on top of a relational database developed in SQL.

The main goals of this analysis are:
- To understand sales behavior over time
- To evaluate performance by product, customer, and region
- To identify patterns, seasonality, and business insights
- To validate data consistency before advanced analytics
  
---
## 🗂 Project Structure
- **sql/**: Database creation scripts, data population, and business rules
- **notebooks/**:
  - `01_EDA_Vendas.ipynb`: Exploratory Data Analysis using Python
- **model/**: Relational database model and documentation

---
## 🧱 Data Model Overview
The analysis is based on a consolidated fact table created from the following entities:
- Customers
- Products and product categories
- Orders and order items
- States (regions)
- Pricing and sales values

The fact table ensures:
- Temporal consistency of sales
- Correct aggregation of quantities and monetary values
- Reliable analytical relationships between entities

---
## 🔍 Approach / Analysis Performed
### Descriptive Analysis
- Distribution of prices and total sales values
- Identification of skewness and outliers
- Relationship between quantity sold and total value

### Product Analysis
- Sales volume by product
- Revenue contribution by product
- Average ticket per product

### Regional Analysis
- Quantity sold by state
- Revenue by state
- Average ticket by state
- Comparison between volume and profitability across regions

### Temporal Analysis
- Monthly revenue evolution
- Comparison between 2023 and 2024
- Identification of seasonal patterns
- Performance comparison of top-performing states over time

---
## 📊 Key Insights

### Revenue Concentration Across Products

The analysis shows a strong concentration of revenue in a few key products. Chocolate alone accounts for approximately 40% of total revenue, followed by Strawberry with around 25%.

This distribution indicates a Pareto-like behavior, where a small number of products drive the majority of the business performance.

  <p align="center">
  <img width="630" height="376" alt="image" src="https://github.com/user-attachments/assets/f60665e8-76ec-4dfa-8627-0337c72882b3" />
</p>

This concentration highlights the strategic importance of top-performing products, while also suggesting potential opportunities to improve the performance of lower-selling items.

---

### Revenue Volatility and Growth Stability (MoM)

The month-over-month (MoM) revenue variation highlights a clear difference in volatility between 2023 and 2024.

In 2023, revenue shows strong fluctuations, including sharp drops and significant spikes — especially a pronounced increase around September — indicating an unstable growth pattern.

In contrast, 2024 presents a more controlled and consistent behavior, with smoother variations and fewer extreme changes throughout the year.

<img width="621" height="392" alt="image" src="https://github.com/user-attachments/assets/4f16f537-1e22-4320-902c-119be8af2111" />

This pattern suggests that the business became more stable over time, potentially reflecting a more consolidated customer base, improved demand predictability, and a more structured sales cycle.

---
## 🧠 Conclusion

The analysis shows that revenue is driven by a combination of sales volume and average ticket. Top-performing products and regions tend to combine both high volume and higher value per transaction.

However, this relationship is not consistent across all cases, indicating that different products and regions may generate revenue through distinct strategies — either through high frequency of sales or higher value per order.

These findings highlight the importance of analyzing volume and ticket together to better understand business performance and support decision-making.

---
## ⚙️ Technologies  
- Python (Pandas, NumPy)
- SQL (DuckDB)
- Data visualization (Matplotlib, Seaborn)
- Jupyter Notebook

---
## 🛠 How to Run
1. Ensure Python is installed
2. Clone the repository
3. Install required libraries:
   ```bash
   pip install pandas duckdb matplotlib seaborn
4. Run the notebooks in the /Notebooks folder

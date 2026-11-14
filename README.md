# E-Commerce Sales Analysis (Superstore)

Exploratory data analysis of a retail store's sales and profit using Python, Pandas and Plotly.

> Completed as part of the iScale "E-Commerce Sales Analysis" guided project, using the public *Sample - Superstore* dataset.

## Business Questions
1. Which months had the highest and lowest sales?
2. Which categories and sub-categories sell the most and the least?
3. Which month is the most profitable?
4. Which categories and sub-categories make or lose profit?
5. How do sales and profit differ across customer segments?
6. What is the profit margin by segment?

## Dataset
- Sample - Superstore: 9,994 orders, January 2014 to December 2017
- Key columns: Order Date, Category, Sub-Category, Segment, Sales, Profit

## Tools
Python, Pandas, Plotly, Jupyter Notebook

## Key Findings
- Total sales: about $2.30M; total profit: about $286K (12.5% margin).
- Sales peak in **November ($352K)** and **December ($325K)**; the lowest month is **February ($60K)**.
- Profit is highest in **December ($43K)** and lowest in January ($9K).
- **Technology** leads in both sales ($836K) and profit ($145K).
- **Furniture** sells well ($742K) but earns only about $18K profit (~2.5% margin).
- **Tables, Bookcases and Supplies** are loss-making; Tables lose about $17.7K on $207K sales.
- **Consumer** is the biggest segment but has the lowest margin (11.55%). Corporate is 13.03% and Home Office 14.03%.
- Sales grew every year from 2015 ($471K) to 2017 ($733K).

## Recommendations
- Review discounts and pricing on Tables and Bookcases.
- Plan inventory and marketing around the September to December peak.
- Focus on cost control in the Consumer segment.

## How to Run
```bash
git clone https://github.com/aryanbhardwaj-tech/ecommerce-sales-analysis.git
cd ecommerce-sales-analysis
pip install -r requirements.txt
jupyter notebook ecommerce-sales-analysis.ipynb
```

## Author
**Aryan Bhardwaj** | [GitHub](https://github.com/aryanbhardwaj-tech)

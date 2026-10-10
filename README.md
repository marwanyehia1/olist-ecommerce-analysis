# Olist E-commerce Data Analysis

## Project Overview

An end-to-end exploratory data analysis project using the Olist Brazilian e-commerce dataset. This project investigates sales performance, customer purchasing behavior, delivery reliability, product categories, seller performance, customer satisfaction, and payment trends using Python.

## Business Objectives

- Evaluate order fulfillment and delivery performance.
- Identify revenue-driving product categories and geographic markets.
- Analyze customer retention and repeat-purchase behavior.
- Investigate the relationship between delivery delays and customer reviews.
- Compare seller delivery performance.
- Understand payment methods and installment patterns.

## Tools & Technologies

- **Python**
- **Pandas** - data cleaning, transformation, aggregation, and analysis
- **NumPy** - conditional logic and numerical calculations
- **Matplotlib & Seaborn** - data visualization
- **Jupyter Notebook / VS Code** - analysis workflow

## Key Findings

### Sales Performance
- **99,441** total orders.
- **96,478** delivered orders.
- **R$15.42 million** in delivered product and freight revenue combined.
- **R$137.04** average delivered-order product value.

### Customer Behavior
- **93,358** unique customer identities among delivered orders.
- Most customers purchased only once.
- Repeat customers generated higher average customer revenue than one-time customers.

### Delivery & Customer Satisfaction
- On-time or early orders had an average review score of **4.29/5**.
- Orders delayed by 15 or more days had an average review score of **1.71/5**.
- Longer delivery delays were strongly associated with lower customer ratings.

### Geographic Performance
- São Paulo contributed approximately **38.33%** of delivered product revenue.
- Delivery times and late-delivery rates varied across Brazilian states.

### Seller Performance
- Compared sellers with at least 100 seller-orders to reduce the impact of very small samples.
- Observed late-order rates varied substantially between sellers.

### Payment Behavior
- Credit cards represented approximately **78.34%** of recorded payment value.
- One-installment payments were the most frequent installment category.

## Methodology

1. Loaded and inspected the Olist datasets.
2. Examined missing values, duplicates, and data types.
3. Standardized selected product-category and date fields.
4. Created order-delivery metrics and status classifications.
5. Aggregated order items and payments separately before combining them to avoid double-counting from one-to-many relationships.
6. Analyzed revenue, product categories, customer behavior, geographic performance, reviews, sellers, and payment methods.
7. Visualized key patterns and developed business recommendations.

## Business Recommendations

- Investigate the causes of long delivery delays and improve proactive customer communication.
- Test retention campaigns designed to encourage second purchases.
- Monitor delivery performance by region and seller while accounting for differences in order volume and logistics conditions.
- Track product revenue separately from freight revenue.
- Use payment preferences to inform checkout and customer-experience improvements.

## Limitations

This analysis is observational. Relationships between delivery delays and customer ratings do not, by themselves, establish causation. Seller and regional comparisons may be affected by product mix, geography, shipping providers, and order characteristics.

## Repository Contents

- `olist_ecommerce_analysis.ipynb` — data preparation, exploratory analysis, visualizations, and business findings.
- `requirements.txt` — Python dependencies.
- `images/` — selected project visuals, if included.

## How to Run

1. Download the Olist dataset from its original public source.
2. Place the CSV files in the expected `data/raw/` directory.
3. Install the required Python packages.
4. Open the notebook in Jupyter Notebook or VS Code.
5. Run the cells from top to bottom.

## Author

**Marwan Yehia**

Aspiring Data Analyst | Python | SQL | Power BI

[GitHub Portfolio](https://github.com/marwanyehia1)
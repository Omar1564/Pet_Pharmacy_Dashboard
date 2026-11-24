# Pet Pharmacy Inventory & Supplier Dashboard (Power BI)

An interactive Power BI dashboard that tracks inventory, products and suppliers for a veterinary pet pharmacy. It helps answer: **which suppliers account for most of the inventory value, and which products drive the most revenue and stock?**

> **Data note:** [EDIT BEFORE PUBLISHING: write the real source here, for example "Sample inventory data for a pet pharmacy, with names and prices anonymized" or "Synthetic data created for practice". Do not publish a real business's data without permission.]

## Dashboard pages
| Page | What it shows |
|---|---|
| Main Page | Navigation to the report sections |
| Overview | KPI cards (total value, total quantity, number of products, number of suppliers, average unit price), supplier share (pie and bar charts), top products, supplier and product slicers |
| Supplier Analysis | Per-supplier table (quantity, total value, average unit price), each supplier's % contribution with up/down indicators, top 3 suppliers, supplier ranking chart |
| Product Analysis | Products classified High / Low by revenue, top 10 products by sales, top 10 products in stock |
| Drill-through (WHY) | Supplier to product breakdown (decomposition tree) with a tooltip for each product |

## Key numbers shown in the report
- 11 suppliers and 134 products
- Total quantity: 2,100 units
- Total value: 724,512 (the report labels it "Total Sales")
- Average unit price: 624.40
- Top 3 suppliers by value: المنار (177,097), ماك فارما (154,430), حسن الهلالي (106,320). Together they account for about 60% of the total.

## Tools and skills used
- Microsoft Excel for the source sheet (136 rows: product ID, supplier, product name, quantity, unit price, total price)
- Power Query for cleaning and shaping the data
- Power BI Desktop for the data model, visuals, slicers, navigation buttons and drill-through
- DAX measures for totals, averages, supplier contribution % and High/Low revenue classification

## How to open
1. Download `Pet_Pharmacy_Dashboard.pbix` from this repo.
2. Open it with Power BI Desktop (free).
3. Use the supplier and product slicers on the left to filter every page.

## Dashboard

(main.png)
(overview.png)
(products.png)
(suppliers.png)
(drill-through.png)

## Possible next steps
- Add stock-out and reorder-level alerts
- Add a time dimension (monthly sales) to track trends
- Publish a version with anonymized data

## Author
Omar Elzawawy | Junior Data Analyst | [LinkedIn](https://www.linkedin.com/in/omar-elzawawy-71959b25b) | [GitHub](https://github.com/Omar1564)

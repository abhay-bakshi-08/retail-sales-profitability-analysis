Retail Sales & Profitability Analysis

End-to-end analysis of a retail transactions dataset using Excel, SQL, and Power BI.

Dataset
10,194 transactions across 5,111 unique orders
3 categories: Technology, Furniture, Office Supplies
4 regions: West, East, Central, South — covering 59 states/provinces (includes Canadian provinces such as Ontario and Quebec, alongside U.S. states)
Date range: January 3, 2023 – December 30, 2026 (4 full years)
Key Findings

Headline dashboard metric: Total Sales ($2.33M), with Total Profit ($292.30K), Total Quantity (39K units), and Total Orders (5K) as supporting KPIs.

Top performer:

By sales: Technology — $839,893 vs. Furniture's $754,748 (~$85K / ~11% higher)
By profit: Technology — $146,543 vs. Office Supplies' $126,023 (~$20.5K / ~16% higher)
By region: West leads on both sales ($739,814) and profit ($110,799) — roughly $48K ahead of East on sales and $16K ahead on profit

Weakest performer:

Furniture is the weakest category by margin. Despite generating the 2nd-highest sales ($754,748), it produced only $19,730 in profit — a 2.6% margin, compared to ~17% for Technology and Office Supplies
The specific loss-maker is the Tables sub-category, at -$17,753 total profit. Bookcases (-$3,632) and Supplies (-$1,171) are also unprofitable

Counterintuitive insight: High sales don't guarantee high profit. Furniture ranks #2 in revenue but has a margin 6–7x worse than the other two categories, and the entire drag comes down to one sub-category — Tables — being sold at a net loss, most likely driven by heavy discounting. This directly informed the recommendation to monitor profitability alongside sales rather than sales alone.

Tools & Workflow
Excel — data cleaning, pivot tables, initial KPI calculation
SQL (PostgreSQL) — aggregation, ranking, segmentation, and cohort analysis (retail_sales_analysis.sql)
Power BI — interactive dashboard with KPI cards, category/regional breakdowns, monthly trend, and year/region filters
Files
retail_sales_data.csv — cleaned transaction-level dataset
retail_sales_analysis.sql — SQL queries used for business analysis
retail_sales_analysis.xlsx — Excel pivot tables and KPI calculations
retail_sales_dashboard.pbix — Power BI dashboard file
project_documentation.pdf — full write-up of methodology and findings

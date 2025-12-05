# Credit_Card-Financial-Dashboard
Credit Card Financial Dashboard

Overview:
This project presents an interactive Power BI dashboard built to analyze credit card customer and transaction data. 
It converts raw financial records into clear insights related to spending, customer behavior, delinquency patterns, and risk monitoring.
The dashboard demonstrates skills in SQL-based data extraction, DAX measures, data modeling, and business-focused visualization.

Dashboard Features:
- Spending and usage trends including total spend, average spend, and transaction counts
- Risk and delinquency analysis with identification of delayed or high-risk customers
- Customer segmentation based on activity, frequency, and transaction volume
- KPI summary showcasing outstanding balance, credit utilization, active/inactive customer distribution, and delinquency rate
- Interactive filters for date, customer type, risk segmentation, and other dimensions
- Transparent workflow with dataset, cleaning steps, and the Power BI file provided

Tools and Technologies:
Power BI Desktop
SQL for extraction and transformation
DAX for analytics and measures
Excel/CSV (if dataset was provided in these formats)



Sample DAX Measures:
Total Spend = SUM(Transactions[Amount])

Delinquency Rate =
DIVIDE(
    CALCULATE(COUNTROWS(Transactions), Transactions[Status] = "Delinquent"),
    COUNTROWS(Transactions)
)

How to View the Dashboard:
1. Download the .pbix file
2. Open in Power BI Desktop
3. Load or refresh the dataset if needed
4. Use slicers and filters to explore insights and customer patterns

Skills Demonstrated:
- SQL querying and data cleaning
- DAX formulas for analytical computation
- Data modeling and relationship management
- Visual storytelling with Power BI
- Business understanding of financial KPIs

Contact:
Raktim Banerjee
Email: raktimbanerjee67@gmail.com
LinkedIn: linkedin.com/in/raktim-banerjee
GitHub: github.com/RAKTIM04


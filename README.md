# Assignment-Task-Overview-POWETR-BI
In this assignment, you will use DAX (Data Analysis Expressions) in Power BI to create  calculated columns and measures that generate meaningful business metrics. You will  then develop interactive visualizations to analyze sales trends, profitability, and  performance indicators within the e-commerce business environment.
📊 Project Title: 
Assignment Task Overview
The focus of this assignment is on DAX calculations, analytical thinking, and visual 
storytelling, while ensuring that the underlying data model supports accurate reporting 
and insights.
🎯 Project Overview
•	Business Problem: State the clear problem or question this analysis targets.
•	Objective: Explain what the business will achieve by using this dashboard.
•	Target Audience: Identify the primary users (e.g., CATEGORY OF PRODUCT, SALES TARGRT).
🗃️ Data Sources & Architecture
•	Source Systems: List sources like SQL Server, Salesforce, or local Excel files.
•	Data Volume: Note the rough row counts or timeframe covered.
•	Storage Mode: Specify if using Import, DirectQuery, or Composite mode.
⚙️ Data Transformation (ETL)
•	Tool Used: Power Query Editor.
•	Key Cleanups: List standard transformations applied to raw data  DAX calculations, analytical thinking
•	Custom Functions: Mention any customized M code scripts used.
🧠 Data Model & DAX
•	Fact Tables: Name the primary transactional tables.
•	Dimension Tables: Name the lookup tables, including your dedicated Date table.
•	Key Measures:
•	Order Count = COUNTROWS('Order Details')

•	Revenue = 'Order Details'[Amount] * 'Order Details'[Quantity]


•	Total Orders = DISTINCTCOUNT('Order Details'[Order ID])

•	TOTAL PROFIT = SUM('Order Details'[Profit])


•	Total Sales = SUM('Order Details'[Amount])

•	MinTarget = min('Sales target'[Target])


•	Target Sales = SUM('Sales target'[Target])

•	Variance % = DIVIDE([Total Sales] - [Target Sales], [Target Sales], 0)

💡 Key Insights
•	the business demonstrates strong sales performance, but focusing on underperforming categories and regions can further improve growth and profitability.

🚀 How To Use
1.	Prerequisites: Ensure you have the latest Power BI Desktop installed.
2.	File Formats: Clone the repository to access the .pbix or .pbit file.
3.	Data Refresh: Change the source path under Data Source Settings to point to your data files.


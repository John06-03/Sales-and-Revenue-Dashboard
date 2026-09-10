# 📊 Sales & Business Performance Dashboard — Power BI

A portfolio Power BI project analyzing sales performance across products, categories, regions, states and customer segments.

## Dataset
1,200 synthetic sales records covering 2025. The CSV contains order, date, customer, segment, region, product, quantity, discount, sales and profit fields.

## Dashboard Pages
1. Executive Overview — KPIs, monthly trend, regions, categories, top products and segments.
2. Product Analysis — category, sub-category, product and quantity performance.
3. Regional & Customer Analysis — state/region, customer and segment performance.

## Tools
Power BI Desktop, Power Query, DAX, CSV, Data Visualization.

## Build
1. Open Power BI Desktop.
2. Get Data -> Text/CSV -> Sales_Data.csv.
3. Follow Power_Query_Steps.txt.
4. Create the Date table and measures from DAX_Measures.txt.
5. Create Date[Date] -> Sales_Data[Order_Date] relationship.
6. Build pages according to Dashboard_Layout.txt.
7. Save as `Sales_Performance_Dashboard.pbix`.

## GitHub Structure
```text
Sales_Performance_PowerBI/
├── Sales_Data.csv
├── DAX_Measures.txt
├── Power_Query_Steps.txt
├── Dashboard_Layout.txt
├── Resume_Project_Description.txt
├── README.md
└── Sales_Performance_Dashboard.pbix
```

The `.pbix` file must be saved from Power BI Desktop and added to the repository.

Note: The dataset is synthetic and intended for learning/portfolio use.

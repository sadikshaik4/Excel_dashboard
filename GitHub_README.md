# 📊 Financial Sales & Profitability Dashboard (Excel)

An interactive Excel dashboard built on the **Financial Sample** dataset to analyze sales performance, discounting behavior, and profitability across regions, segments, and products.

## 📁 Dataset
- **Rows:** 700 transactions
- **Time period:** 2013–2014
- **Countries:** Canada, Germany, France, Mexico, United States of America
- **Segments:** Government, Enterprise, Midmarket, Channel Partners, Small Business
- **Products:** Carretera, Paseo, Velo, VTT, Amarilla, Montana
- **Fields:** Segment, Country, Product, Discount Band, Units Sold, Manufacturing Price, Sale Price, Gross Sales, Discounts, Sales, COGS, Profit, Date

## 🎯 Objective
Turn raw transactional sales data into a decision-ready, interactive dashboard that lets a business user filter by year, segment, country, and product to instantly see how sales, profit, and volume shift.

## 🛠️ Tools & Techniques
- **Excel PivotTables & PivotCharts** for aggregating sales, profit, and units by month, product, and discount band
- **Slicers** for Year, Segment, Country, and Product to enable interactive filtering
- **KPI cards** for Total Sales, Total Profit, and Total Units Sold, updating dynamically with slicer selections
- Data cleaning and structuring of raw transactional data into pivot-ready format

## 📈 Key Insights
- **Total Sales:** ~$25M | **Total Profit:** ~$3M | **Total Units Sold:** ~232,600+
- Sales trended upward through the year, **peaking in Q4 (Oct–Dec)**, indicating strong seasonal demand
- **Paseo and VTT** were the highest profit-generating products, while Carretera had the lowest profit despite steady volume
- **High-discount transactions** accounted for the largest share of units sold — highlighting a volume-vs-margin trade-off worth monitoring
- **Government and Midmarket** segments contributed the largest share of transactions

## 📸 Dashboard Preview
*(Add a screenshot of your dashboard here — export the `dashboard` sheet as an image and place it in the repo, e.g. `dashboard_preview.png`)*

```markdown
![Dashboard Preview](dashboard_preview.png)
```

## 📂 Repository Structure
```
├── Financial_Sample.xlsx              # Raw dataset
├── Financial_Sample_Dashboard.xlsx    # Final interactive dashboard
├── dashboard_preview.png              # Screenshot of the dashboard
└── README.md
```

## 🚀 How to Use
1. Download `Financial_Sample_Dashboard.xlsx`
2. Open in Excel (Slicers and PivotCharts require Excel 2016+)
3. Use the slicers at the top of the dashboard to filter by Year, Segment, Country, or Product
4. KPI cards and charts update automatically based on your selection

## 🔗 Connect
If you found this useful or have feedback, feel free to connect with me on [LinkedIn](https://linkedin.com/in/sadik-shaik-646181284).

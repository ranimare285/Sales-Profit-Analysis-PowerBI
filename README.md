# 🛒 Nova Mart — Sales & Profit Analysis Dashboard

## 📌 Project Overview

**Nova Mart Sales & Profit Analysis** is an interactive Power BI dashboard built to analyze sales, profit, quantity, discounts, customers, products, cities, states, and regions.

The project uses a sales dataset containing **3,000 order records** covering **2023–2025** and presents the analysis through multiple Power BI report pages.

The dashboard is designed to answer practical business questions such as:

- How much sales and profit has Nova Mart generated?
- Which customers contribute the most sales?
- Which products generate the highest sales and profit?
- Which regions and states contribute the most profit?
- How are sales distributed across products and regions?
- How does sales performance change by month?
- How do cost, unit price, discount, and profit vary geographically?

---

## 🛠️ Tools & Technologies

- **Power BI**
- **DAX**
- **Power Query**
- **Microsoft Excel / CSV**
- **Data Visualization**
- **Business Intelligence**

---

## 📂 Project Structure

```text
Nova_Mart_Sales_Dashboard/
│
├── README.md
├── DATA_DICTIONARY.md
├── DAX_MEASURES.md
├── requirements.txt
├── .gitignore
│
├── data/
│   └── Sales_Data.csv
│
└── powerbi/
    └── Sales_Project.pbix
```

---

## 📊 Dataset Overview

The source dataset contains:

| Metric | Value |
|---|---:|
| Records | 3,000 |
| Columns | 15 |
| Date Range | 2023–2025 |
| Customers | 499 |
| Products | 10 |
| Categories | 3 |
| Regions | 5 |
| States | 10 |
| Cities | 10 |

### Key KPI totals

Based on the uploaded dataset:

| KPI | Total |
|---|---:|
| Sales | ₹348.94M |
| Profit | ₹83.83M |
| Quantity | 31.39K |
| Discount | 22.33K |
| Orders | 3K |

The dashboard displays rounded KPI values such as **349M Sales**, **84M Profit**, **31K Quantity**, **22K Discount**, and **3K Order ID count**.

---

# 📑 Dashboard Pages

## 1. Sales Dashboard

The Sales Dashboard provides a high-level view of overall sales performance.

### Main KPIs

- Sum of Sales
- Sum of Profit
- Sum of Quantity
- Sum of Discount
- Count of Order ID

### Visuals

- Top 10 Customers by Sales
- Top 5 Products by Sales
- Total Sales by Product
- Sales by Region
- Product slicer
- Category slicer
- City slicer
- State slicer
- Region slicer
- Order Date range filter

---

## 2. Profit Analysis

The Profit page focuses on geographical and product-level profitability.

### Key visuals

- Region-wise Profit
- Sum of Discount by Product
- Sum of Profit by Product
- Profit by City and Category
- Sum of Profit by State
- Products by Discount
- Products by Unit Price
- State by Profit, Cost and Unit Price
- Sum of Cost by Region
- Sales by Month

### KPI Cards

- Maximum Profit
- Maximum Sales

---

## 3. City & Region Analysis

The third dashboard page provides additional geographical analysis of the business.

It can be used to investigate:

- City-level performance
- Regional performance
- Product performance by location
- Sales and profit distribution
- Geographic business trends

---

# 🔍 Key Business Analysis Areas

### Customer Analysis
Identifies high-value customers based on sales contribution.

### Product Analysis
Compares products using:

- Sales
- Profit
- Quantity
- Discount
- Unit Price

### Regional Analysis
Compares:

- North
- South
- West
- East
- Central

### State Analysis
Provides state-level comparisons of sales, profit, cost, and pricing.

### City Analysis
Analyzes sales/profit performance across cities and product categories.

### Time Analysis
The dashboard covers orders from **January 2023 through December 2025** and includes monthly sales analysis.

---

# 🎨 Dashboard Design

The dashboard uses a high-contrast business intelligence design:

- Black chart backgrounds
- Green KPI cards
- Orange filters and chart elements
- White titles and labels
- Blue/purple/pink/green chart accents
- Interactive slicers
- KPI cards for quick performance monitoring

This layout is designed to make important business metrics easy to identify while keeping detailed analysis available through interactive visuals.

---

# 🚀 How to Use

## 1. Clone the repository

```bash
git clone https://github.com/your-username/Nova_Mart_Sales_Dashboard.git
cd Nova_Mart_Sales_Dashboard
```

## 2. Open the Power BI file

Open:

```text
powerbi/Sales_Project.pbix
```

using **Power BI Desktop**.

## 3. Refresh the data

If the CSV path changes after cloning the repository, update the Power Query source path to:

```text
data/Sales_Data.csv
```

Then select **Refresh** in Power BI.

---

# 📈 Skills Demonstrated

This project demonstrates practical skills in:

### Power BI
- Dashboard development
- Data modeling
- Interactive slicers
- KPI cards
- Drill-down analysis
- Business-oriented visualization
- Cross-filtering
- Multiple-page report design

### DAX
- Aggregation measures
- SUM
- COUNT
- MAX
- Filter-based calculations
- KPI calculations

### Data Analytics
- Sales analysis
- Profitability analysis
- Customer analysis
- Product analysis
- Geographic analysis
- Time-series analysis

---

# 💼 Portfolio Value

This project demonstrates an end-to-end **Business Intelligence / Data Analyst** workflow:

```text
Raw Sales Data
      ↓
Data Preparation
      ↓
Data Modeling
      ↓
DAX Measures
      ↓
Interactive Power BI Dashboard
      ↓
Business Insights
```

It can be used as a portfolio project to demonstrate practical Power BI and data-analysis skills.

---

## 👩‍💻 Author

**Rani**

Data Analytics | Python | SQL | Power BI | Pandas

---

## ⭐ Future Improvements

Possible extensions include:

- Add Year-over-Year sales growth
- Add Month-over-Month growth
- Add profit margin analysis
- Add category-level KPIs
- Add customer segmentation
- Add dynamic Top N analysis
- Add drill-through pages
- Add tooltip pages
- Add automated data refresh

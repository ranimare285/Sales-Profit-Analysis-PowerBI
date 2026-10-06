# 📐 Nova Mart Power BI — Suggested DAX Measures

These measures correspond to the KPI and analytical fields visible in the dashboard. Adjust the table name if your Power BI model uses a different table name.

Assuming the table is named `Sales_Data`:

## 1. Total Sales

```DAX
Total Sales =
SUM(Sales_Data[Sales])
```

## 2. Total Profit

```DAX
Total Profit =
SUM(Sales_Data[Profit])
```

## 3. Total Quantity

```DAX
Total Quantity =
SUM(Sales_Data[Quantity])
```

## 4. Total Discount

```DAX
Total Discount =
SUM(Sales_Data[Discount])
```

## 5. Total Orders

```DAX
Total Orders =
COUNT(Sales_Data[OrderID])
```

## 6. Maximum Profit

```DAX
Max Profit =
MAX(Sales_Data[Profit])
```

## 7. Maximum Sales

```DAX
Max Sales =
MAX(Sales_Data[Sales])
```

## 8. Profit Margin

```DAX
Profit Margin =
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
)
```

## 9. Total Cost

```DAX
Total Cost =
SUM(Sales_Data[Cost])
```

## 10. Average Unit Price

```DAX
Average Unit Price =
AVERAGE(Sales_Data[UnitPrice])
```

## 11. Average Discount

```DAX
Average Discount =
AVERAGE(Sales_Data[Discount])
```

## 12. Sales per Order

```DAX
Sales per Order =
DIVIDE(
    [Total Sales],
    [Total Orders],
    0
)
```

## 13. Profit per Order

```DAX
Profit per Order =
DIVIDE(
    [Total Profit],
    [Total Orders],
    0
)
```

## Note

The formulas above are portfolio-ready suggested measures based on the fields and KPIs shown in the supplied dashboard screenshots. Verify the exact measure names and formulas inside `Sales_Project.pbix` before documenting them as the original model definitions.

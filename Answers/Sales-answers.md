# Excel Challenge Answers

### 1. Total Sales Calculation
Formula:  
`= Units Sold * Unit Price`

### 2. Total Sales Value
Formula:  
`=SUM(Total Sales Range)`

### 3. Average Units Sold
Formula:  
`=AVERAGE(Units Sold Range)`

### 4. Conditional Formatting
To highlight **Total Sales** exceeding $60,000:
- Select the **Total Sales** column.
- Go to **Home** > **Conditional Formatting** > **Highlight Cells Rules** > **Greater Than**, and enter `60000`.

### 5. COUNTIF for Units Sold
Formula:  
`=COUNTIF(Units Sold Range, ">50")`

### 6. Data Validation for Region
To add a dropdown list for the **Region** column:
- Select the **Region** cells.
- Go to **Data** > **Data Validation** > **List**, and enter your regions.

### 7. Pivot Table for Total Sales by Product and Region
- Select your dataset.
- Go to **Insert** > **PivotTable**.
- Drag **Product** to Rows, **Region** to Columns, and **Total Sales** to Values.

### 8. IF Function for Total Sales
Formula:  
`=IF(Total Sales > 50000, "Exceeded", "Not Exceeded")`

### 9. VLOOKUP for Sales Target
Formula to check if total sales exceed $45,000:  
`=IF(VLOOKUP(A2, SalesTable, Total Sales Column, FALSE) > 45000, "Above Target", "Below Target")`

### 10. SUMIFS for Total Sales of Tablets in the West Region
Formula:  
`=SUMIFS(Total Sales Range, Product Range, "Tablet", Region Range, "West")`

### 11. COUNTIFS for Laptop Sales in the North Region
Formula:  
`=COUNTIFS(Product Range, "Laptop", Region Range, "North")`

### 12. Bar Chart for Total Sales by Product
- Select your **Product** and **Total Sales** data.
- Go to **Insert** > **Bar Chart**.

### 13. Filter for Smartphone Sales
- Select your dataset.
- Go to **Data** > **Filter**, then click the filter arrow in the **Product** column and select **Smartphone**.

### 14. Sort by Total Sales
- Select the **Total Sales** column.
- Go to **Data** > **Sort Z to A**.

### 15. Date Formatting
To format the **Date** column as **"MMM-YYYY"**:
- Select the **Date** column.
- Right-click and select **Format Cells** > **Custom**, then enter `MMM-YYYY`.

# sales_google_sheets
This project analyzes basic sales data using Google Sheets. It includes key metrics, conditional formatting, summary tables, and data visualization. A good beginner project for practicing spreadsheet formulas and dashboard creation.

# Sales Analysis - Google Sheets Project

This is a basic **sales analysis project** done in **Google Sheets** to understand key formulas, data formatting, and dashboards.

👉 
<a href="https://docs.google.com/spreadsheets/d/1JJnm-A-2h19ME75FgPVakAsbSXQQ67JaFcceIkErc0Y/edit?usp=sharing">View Sales Analysis Google Sheet<a/>
---

## 📊 Project Overview

In this project, I practiced and applied the following skills:

- Data entry and formatting
- Use of formulas like `SUM`, `AVERAGE`, `COUNTIF`, `SUMIF`, `IFNA`, and `MODE`
- Creating a summary table
- Applying **conditional formatting**
- Adding new fields like **salesperson category**
- Making the data look clean and useful

---

## 📁 Project Structure

**Raw Data** : Sales data including product name, quantity, price, and total sales 
**New Columns** : Added sales category based on high or low sales 
**Summary Table** : Key metrics like total sales, average sale, count of high sales 
**Formatting** : Conditional formatting to highlight important rows 
**Extra Functions** : Used `IFNA` to avoid errors, and formulas for clean output 

---

## 📌 Key Formulas Used

| Description           | Formula                              |
|-----------------------|------------------------------------|
| Total Sales           | `=SUM(F2:F11)`                     |
| Average Sale          | `=AVERAGE(F2:F11)`                 |
| High Sales Count      | `=COUNTIF(G2:G11, "High Sale")`    |
| High Sales Total      | `=SUMIF(G2:G11, "High Sale", E2:E11)` |
| Max Sale              | `=MAX(F2:F11)`                     |
| Min Sale              | `=MIN(F2:F11)`                     |
| Median Sale           | `=MEDIAN(F2:F11)`                  |
| Mode of Sale Amount   | `=IFNA(MODE(F2:F11), "No Mode Found")` |
| Total Quantity Sale   | `=SUM(D2:D11)`                     |
| Total Sales By Seller | `=SUMIF(C2:C11, J2, F2:F11)`        |
| Total Quantity Sold   | `=SUMIF(C2:C11, J2, D2:D11)`        |

Completed.

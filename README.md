# Sales_Tracker_Dashboard
An Excel based sales tracking dashboard that logs transaction level sales data and rolls it up into a monthly, interactive dashboard view.

Overview

This workbook helps track and visualize 
sales performance across 
products, states, sales, people, 
and payment methods with a month-by-month summary 
view built on top of the raw data.

Sheets

1) Report Tracker – 
Raw transaction log. Each row captures Date, Product, Sales Quantity, Sales Price, Total Sales, State, Salesperson, Payment Method, and Profit.

2) Dashboard – Summary view with a month selector, key metrics (Total Sales, Highest Sale for the Month, etc.), and supporting charts.

3) Support Sheet – Backend reference list used to power dropdowns/filters on the Dashboard.

How to Use

1) Open the workbook in Excel.

2) Log new sales in the Report Tracker sheet, one row per transaction.

3) Go to the Dashboard sheet and select a month from the dropdown.

4) The KPIs and charts update automatically based on the selected month.

Features


1) Month-wise filtering of sales data

2) Auto-calculated KPIs 

3) Visual charts for quick performance insights

4) Breakdown by Product, State, Salesperson, and Payment Method

Formulas Used

1) SUM- Adds up sales for the filtered/selected month

2) FILTER- Pulls only the rows from Report Tracker matching the selected month

3) SORT- Sorts the filtered rows (used together with FILTER)

4) TEXT()- Converts each transaction date to a month name

5) XLOOKUP()- To lookup a value from the table and return

Tools Used

Google Sheets (formulas, pivot-style summaries, charts, data validation for dropdowns)

Author

[Lakshay Bhatia]





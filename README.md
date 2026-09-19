# retail-inventory-optimization-dashboard
Retail inventory optimization dashboard — Excel, Power BI, Python.
# Retail Inventory Optimization Dashboard

A self-directed analytics project simulating inventory management for **Globus Mart**, a fictional 12-store retail chain across Delhi NCR. Built using Excel, Power BI, and Python to identify stockout and overstock problems and turn them into actionable procurement decisions.

## The Problem

Globus Mart faces two linked inventory issues: fast-moving daily essentials (like mustard oil and butter) frequently run out of stock — an estimated 14% in lost sales — while slow-moving items (like premium cookware and seasonal decor) sit unsold in the warehouse, driving storage costs up by 22%. This project identifies which SKUs need urgent reordering and which are tying up capital unnecessarily.

- 📊 **Excel Workbook** (`Globus Mart Project.xlsx`) — 4-tab workbook (ReadMe, Inventory_Table, Purchase_Hub, Executive_Cockpit) with demand analysis, ABC/XYZ classification, safety stock & reorder point (ROP) calculations, and an executive KPI dashboard
- 📈 **Power BI Dashboard** — interactive version of the same analysis: [live link coming soon]
- 🐍 **Python (pandas)** (`datacleaning.ipynb`) — data validation notebook checking for missing values, duplicate records, and cross-sheet ID consistency, plus currency-format cleanup

## Key Skills Demonstrated

- **Excel:** XLOOKUP, SUMIFS/COUNTIFS/AVERAGEIFS, nested IFS logic, Pivot Tables, Slicers, safety stock/ROP formulas
- **Power BI:** DAX measures, data modeling and relationships, interactive visuals and Top-N filtering
- **Python:** pandas data validation, type conversion, merge-based consistency checks

## Note on the Data

All data is simulated for demonstration purposes. Assumptions (lead times, current stock snapshots, data time range) are documented in the workbook's Read_Me tab.

## Links

- 📊 [Excel Workbook](Globus%20Mart%20Project.xlsx)
- 🐍 [Data Validation Notebook](datacleaning.ipynb)
- 📈 Power BI Dashboard — coming soon

# Sales Performance Dashboard

An interactive sales and revenue analysis dashboard built for an internship project. It helps users track sales performance, profit, customers, products, and segments through clear KPIs, charts, and filters.

## Features

- Import data from Excel (`.xlsx`, `.xls`), CSV, or JSON files
- Paste exported database query results in CSV or JSON format
- KPI cards for:
  - Total customers
  - Total orders
  - Total quantity
  - Total sales
  - Total profit
- Sales versus profit analysis by city
- Monthly profit trend chart
- Top 5 customers by sales
- Top 5 products by sales
- Profit percentage by segment
- Interactive filters for region, category, segment, and channel
- Switchable sales analysis by month, category, or segment
- Responsive layout for desktop and mobile screens

## Technologies Used

- HTML5
- CSS3
- JavaScript
- SheetJS for Excel file import

## How to Run the Project

1. Download or clone this repository.
2. Open the `outputs` folder.
3. Open `internship-sales-dashboard.html` in a web browser.

For a better development experience, open the project in Visual Studio Code and use the Live Server extension.

## Data Format

The dashboard recognizes columns such as:

```text
date
customer
product
category
city
region
segment
channel
sales
profit
quantity
orders

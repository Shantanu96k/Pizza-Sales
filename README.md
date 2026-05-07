# Pizza Sales Analysis — Power BI Dashboard

![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A full sales analysis of a pizza restaurant chain covering 2015,
built in Power BI with interactive slicers, DAX measures, and
drill-through pages.

![Dashboard Overview](screenshots/overview_dashboard.png)

##  Project Overview
Analyze pizza sales data to identify trends, revenue drivers, and customer behavior.

##  Key Insights
- Classic pizzas drove 27% of revenue
- Friday 12–1 PM is peak: 3× avg volume
- The Thai Chicken had highest avg price
- The Brie Carre had lowest order count

## Dashboard pages

### Sales overview
![Overview](screenshots/overview_dashboard.png)

### Sales by category & size
![Category](screenshots/sales_by_category.png)

### Peak hours analysis
![Peak Hours](screenshots/peak_hours_heatmap.png)

### Top & bottom performers
![Top Bottom](screenshots/top_bottom_pizzas.png)


## Dataset

| Field          | Description                        |
|----------------|------------------------------------|
| order_id       | Unique order identifier            |
| order_date     | Date of the order (2015)           |
| order_time     | Time of order placement            |
| pizza_id       | Unique pizza SKU                   |
| pizza_name     | Full pizza name                    |
| category       | Classic / Veggie / Chicken / Supreme|
| size           | S / M / L / XL / XXL               |
| unit_price     | Price per pizza (USD)              |
| quantity       | Number of pizzas in that order line |

- **Rows:** 48,620 order lines
- **Period:** January 2015 – December 2015

## How to open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone this repository: `git clone https://github.com/Shantanu96k/Pizza-Sales.git`
3. Open `dashboard/pizza-sales.pbix` in Power BI Desktop
4. The data is embedded — no external connection needed

## Tools & technologies

| Tool      | Purpose                            |
|-----------|------------------------------------|
| Power BI  | Dashboard creation and visuals     |
| DAX       | Calculated measures and KPIs       |
| SQL       | Exploratory data analysis          |
| Power Query | Data cleaning and transformation |

## License

This project is licensed under the [MIT License](LICENSE).

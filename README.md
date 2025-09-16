# Heavy Power Nutrition (HPN) Sales and Returns Analysis Dashboard




## Overview

This project features a comprehensive Power BI dashboard designed for Heavy Power Nutrition (HPN) to provide in-depth analysis of sales and returns data. The dashboard addresses key business challenges by tracking critical KPIs such as Net Sales, Profit, Orders, and Returns, enabling stakeholders to identify top-performing products, understand return trends, and gain insights into customer behavior. The interactive report offers a dynamic view of performance across various dimensions, including monthly, weekly, quarterly, and yearly breakdowns, facilitating data-driven decision-making.




## Key Features

The HPN Dashboard is structured across five interactive pages, each designed to provide specific insights into business performance:

*   **Home/Summary Page:** Provides a high-level overview of key performance indicators including Ordered Quantity, Total Net Sales, and Total Gross Profit. This page serves as an entry point to the detailed analysis.
*   **Transaction Details:** Delivers a comprehensive breakdown of transaction data, showcasing total transactions, quantity ordered, net sales, and profit margin. It includes visualizations of transactions by customer rating, monthly trends, and geographical distribution by country and state.
*   **Quantity Ordered Details:** Focuses specifically on product quantity ordered, presenting total quantity, net sales, and profit margin. This page offers insights into ordering patterns across customer ratings, monthly periods, and geographical regions.
*   **Net Sales Details:** Provides an in-depth analysis of net sales performance, displaying total net sales, quantity, and profit margin. It allows for examination of net sales by customer rating, monthly trends, and geographical distribution.
*   **Profit Details:** Offers a detailed view of profit margins, including total profit margin, transactions, quantity, and net sales. This page helps in understanding profitability across different customer segments, over time, and by geographical location.
*   **Return & Refund Details:** Dedicated to analyzing product returns and refunds. It highlights key metrics such as return quantity, total refunds, and refund rate. Visualizations include top-performing products by returns and refund value versus gross revenue trends by month and weekday.




## Data

The dashboard leverages data imported from CSV files, structured across several fact and dimension tables to ensure a robust and scalable data model. The primary fact tables include `FactTable_Transaction`, `FactTable_Returns`, and `FactTable_Product_Cost`. These are complemented by dimension tables such as `Lookup_Products`, `Lookup_Customers`, `Lookup_ProductCategory`, `Lookup_ProductSubCategory`, and a `Calendar` table for time-based analysis.

**Key Performance Indicators (KPIs) Tracked:**

*   **Net Sales:** Total revenue after accounting for discounts and returns.
*   **Gross Profit:** Profit generated from sales after deducting the cost of goods sold.
*   **Orders:** Total number of customer transactions.
*   **Returns:** Quantity and value of products returned by customers.
*   **Quantity Sold:** Total units of products sold.
*   **Gross Revenue:** Total sales amount before any deductions.
*   **Total Refunds:** Monetary value of all refunds processed.
*   **Total Discounts:** Total value of discounts applied to sales.
*   **Cost of Goods Sold (COGS):** Direct costs attributable to the production of goods sold.
*   **Average Discount Rate:** Average percentage of discount applied.
*   **Number of Customers:** Unique count of customers.
*   **Customer Rating:** Categorization of customers (Silver, Diamond, Gold) based on transaction volume and revenue.
*   **Refund Rate:** Percentage of gross revenue attributed to refunds.




## Tools & Technologies

*   **Power BI Desktop:** Used for data import, transformation, modeling, DAX calculations, and dashboard design.
*   **DAX (Data Analysis Expressions):** Utilized for creating complex measures and calculated columns to derive key insights and metrics.
*   **Power Query:** Employed for data extraction, transformation, and loading (ETL) processes, including data cleaning and normalization.
*   **Excel/CSV:** Source for the raw business data.




## Dashboard Preview

Here are some screenshots of the HPN Sales and Returns Analysis Dashboard:

### Home/Summary Page
![Home/Summary Page](/images/home.png)

### Transaction Details
![Transaction Details](/images/transaction.png)

### Quantity Ordered Details
![Quantity Ordered Details](/images/qty.png)

### Net Sales Details
![Net Sales Details](/images/netsales.png)

### Profit Details
![Profit Details](/images/profit.png)

### Return & Refund Details
![Return & Refund Details](/images/returns.png)

### Data Model
![Data Model](/images/datamodel.png)




## Usage

To interact with this dashboard, you have two primary options:

1.  **Power BI Desktop:**
    *   Ensure you have Power BI Desktop installed on your computer.
    *   Download the `report.pbix` file from this repository.
    *   Open Power BI Desktop and then open the downloaded `.pbix` file. You will be able to explore the data, interact with the visuals, and review the underlying data model and DAX calculations.

2.  **Power BI Service (Online):**
    *   If the dashboard is published to Power BI Service, you can access it directly via a web browser. (Note: This project currently does not include a published link, but it can be easily deployed to Power BI Service for web access.)




## Insights

This Power BI dashboard provides critical insights for Heavy Power Nutrition (HPN) to optimize business strategies:

*   **Performance Monitoring:** The dashboard effectively tracks key metrics such as Net Sales ($73M), Gross Profit ($48M), and Ordered Quantity (214K), providing a clear snapshot of overall business health.
*   **Customer Segmentation:** The customer rating system (Silver, Diamond, Gold) allows HPN to identify and focus on high-value customers, understanding their transaction patterns and revenue contributions.
*   **Return Analysis:** The dedicated 'Return & Refund Details' page highlights products with the highest return rates and analyzes refund value against gross revenue, enabling HPN to address product quality issues or customer satisfaction concerns proactively. For instance, the dashboard shows a Total Refund of $6M and a Refund Rate of 8%, indicating areas for potential improvement.
*   **Trend Identification:** Visualizations across monthly, quarterly, and yearly bases help in identifying seasonal trends, peak performance periods, and areas requiring strategic intervention. For example, Net Sales and Gross Profit show fluctuations throughout the year, which can inform inventory and marketing decisions.
*   **Geographical Performance:** The ability to break down performance by country and state provides insights into regional market strengths and weaknesses, guiding targeted sales and marketing efforts.
*   **Dynamic Analysis:** The dynamic selection features for top N customers/products in return analysis empower users to drill down into specific areas of interest, fostering a deeper understanding of underlying factors.




## Project Structure

The repository is organized as follows:

```
.
├── assets/
├── Dataset/
├── images/
├── themes/
└── HPN.pbix
```

*   `README.md`: This file, providing an overview of the project.
*   `report.pbix`: The main Power BI Desktop file containing the dashboard.
*   `data/`: This directory contains the raw CSV data files used for the dashboard.
*   `images/`: This directory stores all the screenshots and visual assets used in this README.




## About Me

Hi, I'm Marwan Ibrahim Amin, a passionate Data Analyst with a focus on transforming raw data into actionable insights. I specialize in developing comprehensive business intelligence solutions using tools like Power BI, SQL, and Excel. My goal is to empower businesses with data-driven decision-making capabilities.

Feel free to connect with me on LinkedIn: [Marwan Ibrahim Amin](https://www.linkedin.com/in/marwan-ibrahim-amin/)




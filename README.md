🛒 Online Retail Data Analysis Dashboard (Tableau)
An interactive retail analytics dashboard built using Tableau that explores customer purchase behavior, revenue trends, and global demand. It provides actionable insights for improving sales strategy and customer engagement in the e-commerce sector.

📊 Dashboard Overview
The dashboard is structured to address four key business questions:

Monthly Revenue Trend (2011)

Top 10 Countries by Revenue

Top 10 Customers by Revenue

Global Product Demand by Quantity (Excluding UK)

📈 Visualizations & Insights
1️⃣ Monthly Revenue Trend - 2011
📍 Chart Type: Line Graph
📅 X-Axis: Month (Invoice Date)
💰 Y-Axis: Total Revenue

🔍 Insights:

Revenue steadily increased from June to November, peaking in November 2011, likely due to holiday sales.

A sudden drop is seen in December, possibly due to missing data or end-of-year reporting cutoff.

2️⃣ Top 10 Countries by Revenue
📍 Chart Type: Stacked Bar Chart
🗺️ Dimension: Country
📦 Measures: Revenue & Quantity

🔍 Insights:

Netherlands, EIRE (Ireland), and France generated the highest revenue after the UK.

These countries also showed high unit purchases, indicating both value and volume-driven demand.

Balanced contribution from multiple countries indicates global business potential.

3️⃣ Top 10 Customers by Revenue (Excluding Null IDs)
📍 Chart Type: Vertical Bar Chart
👤 Dimension: Customer ID
💰 Measure: Total Revenue

🔍 Insights:

The top customer (ID: 14646) generated revenue of nearly ₹280K.

There is a sharp drop from the top 3 customers to others, indicating a few high-value clients drive a major share of sales.

4️⃣ Global Product Demand (Excluding UK) – Total Units Sold
📍 Chart Type: Symbol Map
🗺️ Dimension: Country (Longitude/Latitude)
📦 Measure: Quantity Sold

🔍 Insights:

Australia, Japan, Germany, and France show high purchase volumes outside the UK.

Useful for international supply chain planning and global inventory distribution.

📂 Dataset Info
Source: UCI Machine Learning Repository – Online Retail Dataset

Time Period: December 2010 to December 2011

Key Columns: InvoiceNo, StockCode, Description, Quantity, UnitPrice, CustomerID, Country, InvoiceDate

🛠 Tools Used
Tableau – Dashboard Development

Excel / CSV – Dataset handling

Python / Pandas (Optional) – Preprocessing and aggregation (if used in pipeline)

📸 Dashboard Preview
Below is a composite screenshot of the final Tableau dashboard:


(sceenshot/Screenshot 2025-07-03 162413.png)

✅ Key Business Takeaways
High sales in Q4 indicate seasonal spikes.

Focus on top-tier customers could yield higher ROI.

Expansion in countries like France, Japan, and Australia is promising.

Large product quantities shipped globally—logistics optimization opportunities.

🚀 Getting Started
Download Data
Online Retail Dataset

Open Dashboard in Tableau
Open Tableau Desktop / Tableau Public.

Import the dataset (Excel/CSV).

Load the .twbx or .twb dashboard file (if shared).

Interact with filters to explore trends across time, geography, and customers.

📌 Future Enhancements
Integrate with Google Analytics or Shopify API for live tracking.

Add churn prediction using RFM analysis.

Deploy dashboard to Tableau Server or embed in a web app.

🧑‍💻 Author
    PRAVEEN S
📫 praveenspraveens702@gmail.com
🔗 https://github.com/praveen3600

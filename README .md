🛒 Amazon Sales Analysis Dashboard (Power BI)
📘 Overview

The Amazon Sales Dashboard is an interactive Power BI project that visualizes sales performance across India.
It provides insights into sales trends, regional performance, top-selling products, and seller analytics to support data-driven decision-making in e-commerce.

🎯 Objectives

Monitor overall sales performance and order trends.

Identify top-performing states and cities by revenue and order count.

Track seller activity, ratings, and inventory levels.

Evaluate category-wise sales contribution and return rate.

📊 Key Metrics
Metric	Value / Description
💰 Total Sales Amount	₹89.06M
📦 Total Orders	133K
⏳ Pending Orders	679
❌ Cancelled Orders	19K
🚚 Shipped Orders	113K
🔁 Return Rate	14.22%
🧾 Seller Count	29K
⭐ Top Rated Sellers	14K (Rating > 4)
🗺️ Regional Insights
🔝 Top 5 States by Sales Amount

Maharashtra — ₹15.6M

Karnataka — ₹12.0M

Tamil Nadu — ₹8.0M

Telangana — ₹7.9M

Uttar Pradesh — ₹7.2M

🌆 Top 5 Cities by Sales Amount

Bengaluru — ₹8.2M

Hyderabad — ₹6.3M

Mumbai — ₹5.0M

New Delhi — ₹4.4M

Chennai — ₹4.3M

📦 Top 5 Cities by Order Count

Bengaluru — 12.2K

Hyderabad — 9.4K

Mumbai — 7.3K

New Delhi — 6.5K

Chennai — 6.5K

🧾 Seller Analysis

Leading sellers include Cart2India SLP, Cloudtail India, Mimosa Sarees, and Torque Traders.

Sales are concentrated among a few large sellers, with many smaller sellers contributing lower volumes.

Stock level visualizations help identify overstocked or underperforming sellers.

⚙️ Tools & Technologies

Data Preparation: Microsoft SQL Server

Data Visualization: Power BI Desktop

Dataset: Amazon India E-commerce Transactions

DAX Measures Used:

Total Sales = SUM(Amazon[Sale_Amount])
Order Count = COUNT(Amazon[Order_ID])
Return Rate = DIVIDE([Returned Orders], [Total Orders])

📈 Dashboard Pages

Overview Dashboard – KPIs and overall performance summary.

Regional Performance – State-wise and city-wise insights.

Category Analysis – Product category sales and returns.

Seller Insights – Seller performance, ratings, and stock tracking.

📷 Dashboard Preview

(Add your screenshots here — example folder below)

/images/dashboard_overview.png
/images/top_states_cities.png
/images/seller_insights.png

🏁 How to Use

Download the Amazon_Sales.pbix or view the Amazon_Sales.pdf.

Open the file in Power BI Desktop.

Refresh or link your dataset from SQL Server or CSV source.

Use interactive filters for:

Date range

Category

Region

Seller

💡 Insights & Takeaways

Maharashtra and Karnataka lead in both sales and orders.

Bengaluru is the top city by order volume and sales amount.

The return rate (14%) highlights a potential area for quality or logistics optimization.

Cart2India and Cloudtail India stand out as top-performing sellers.

📁 Repository Structure
📦 Amazon-Sales-Analysis
 ┣ 📊 Amazon_Sales.pbix
 ┣ 📄 Amazon_Sales.pdf
 ┣ 🖼️ /images
 ┣ 📘 README.md
 ┗ 📂 /data (optional - SQL scripts or CSV source)

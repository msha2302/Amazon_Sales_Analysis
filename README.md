# 🛒 **Amazon Sales Analysis Dashboard (Power BI)**

## 📘 **Overview**
The **Amazon Sales Dashboard** is an interactive **Power BI project** that visualizes sales performance across India.  
It provides insights into **sales trends**, **regional performance**, **top-selling products**, and **seller analytics** to support data-driven decision-making in e-commerce.

---

## 🎯 **Objectives**
- Monitor overall **sales performance** and **order trends**.  
- Identify **top-performing states and cities** by revenue and order count.  
- Track **seller activity**, **ratings**, and **inventory levels**.  
- Evaluate **category-wise sales contribution** and **return rate**.  

---

## ETL Procedure
**1. Extract**  
- Dataset sourced in Excel/CSV format  

**2. Transform (via Power Query Editor):**  
- Removed nulls and duplicates    
- Cleaned seller, links and region values  
- Aggregated sales metrics for analysis  

**3. Load**  
- Final structured dataset loaded into Power BI for reporting and dashboard creation

## 📷 Dashboard Preview
**Overview:** 
![Dashboard](Amazon_Sales.pdf)

## 📊 **Key Metrics**

| **Metric** | **Value / Description** |
|:------------|:------------------------|
| 💰 **Total Sales Amount** | ₹89.06M |
| 📦 **Total Orders** | 133K |
| ⏳ **Pending Orders** | 679 |
| ❌ **Cancelled Orders** | 19K |
| 🚚 **Shipped Orders** | 113K |
| 🔁 **Return Rate** | 14.22% |
| 🧾 **Seller Count** | 29K |
| ⭐ **Top Rated Sellers** | 14K (Rating > 4) |

---

## 🗺️ **Regional Insights**

### 🔝 **Top 5 States by Sales Amount**
1. **Maharashtra** — ₹15.6M  
2. **Karnataka** — ₹12.0M  
3. **Tamil Nadu** — ₹8.0M  
4. **Telangana** — ₹7.9M  
5. **Uttar Pradesh** — ₹7.2M  

### 🌆 **Top 5 Cities by Sales Amount**
1. **Bengaluru** — ₹8.2M  
2. **Hyderabad** — ₹6.3M  
3. **Mumbai** — ₹5.0M  
4. **New Delhi** — ₹4.4M  
5. **Chennai** — ₹4.3M  

### 📦 **Top 5 Cities by Order Count**
1. **Bengaluru** — 12.2K  
2. **Hyderabad** — 9.4K  
3. **Mumbai** — 7.3K  
4. **New Delhi** — 6.5K  
5. **Chennai** — 6.5K  

---

## 🧾 **Seller Analysis**
- Leading sellers include **Cart2India SLP**, **Cloudtail India**, **Mimosa Sarees**, and **Torque Traders**.  
- Sales are concentrated among a few large sellers, with many smaller sellers contributing lower volumes.  
- **Stock level visualizations** help identify overstocked or underperforming sellers.

---

## ⚙️ **Tools & Technologies**
- **Data Preparation:** Power BI Power Query Editor
- **Data Visualization:** Power BI Desktop  
- **Dataset:** Amazon India E-commerce Transactions  


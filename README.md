# 🚚 Intelligent Logistics & Supply Chain Analytics Dashboard

An enterprise-level logistics analytics project built using Power BI, Power Query, and DAX to analyze operational performance, delivery efficiency, route optimization, fuel consumption, and financial KPIs.

---

# 📌 Project Overview

This project simulates a real-world logistics and supply chain analytics system similar to platforms used by Amazon, DHL, Flipkart, and Swiggy logistics teams.

The dashboard helps analyze:

- Delivery performance
- Fleet utilization
- Route efficiency
- Delay trends
- Fuel cost optimization
- Financial profitability
- Operational bottlenecks

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|----------|
| Power BI | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | KPI Calculations |
| Kaggle Dataset | Logistics Operational Data |

---

# 📂 Dataset

Dataset includes multiple logistics operational tables:

- Loads
- Trips
- Drivers
- Trucks
- Customers
- Delivery Events
- Fuel Purchases
- Facilities
- Routes

---

# 📊 Dashboard Pages

## 1️⃣ Executive Dashboard

Key KPIs:
- Total Revenue
- Total Trips
- Profit Margin
- Fuel Cost
- On-Time Delivery %

Visuals:
- Revenue trends
- Business overview
- KPI cards

---

## 2️⃣ Operational Performance Dashboard

Features:
- Trips by Driver
- Trips by Truck
- Distance vs Delay Analysis
- Fleet Utilization

Insights:
- High-performing drivers
- Underutilized trucks
- Operational inefficiencies

---

## 3️⃣ Delivery Analytics Dashboard

Features:
- On-Time vs Delayed Deliveries
- Delay Trend Analysis
- Facility Performance
- Delay Hotspots

Insights:
- Delivery bottlenecks
- Service quality monitoring
- Facility efficiency tracking

---

## 4️⃣ Financial Analytics Dashboard

Features:
- Revenue vs Cost Analysis
- Profit Margin Trends
- Cost per Mile
- Fuel Expense Analytics

Insights:
- Logistics profitability
- Fuel optimization opportunities
- Cost-heavy operations

---

# 📈 Key DAX Measures

```DAX
Total Revenue = SUM(LOADS[revenue])

Total Trips = COUNT(TRIPS[trip_id])

Profit = [Total Revenue] - [Total Fuel Cost]

Profit Margin =
DIVIDE([Profit], [Total Revenue])

Avg Delay Minutes =
AVERAGE(DELIVERY_EVENTS[detention_minutes])
```

---

# 🧠 Business Insights Generated

- Identified delay-prone operational regions
- Analyzed fleet performance and utilization
- Tracked delivery service quality
- Evaluated logistics profitability
- Monitored fuel efficiency trends

---

# 📌 Key Features

✔ Interactive dashboards  
✔ KPI-driven analytics  
✔ Multi-page reporting system  
✔ Advanced DAX calculations  
✔ Data modeling using star schema  
✔ Time-series trend analysis  
✔ Operational & financial intelligence  

---

# 📷 Dashboard Screenshots

_Add screenshots here_

---

# 🚀 Future Improvements

- Real-time data integration
- Predictive analytics using Python
- AI-based route optimization
- IoT fleet monitoring integration

---

# 👨‍💻 Author

Developed by Sherjin A G


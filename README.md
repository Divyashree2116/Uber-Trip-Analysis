## 📷  Dashboard Screenshots:
![OverviewAnalysis of Uber Trip Analysis](https://github.com/user-attachments/assets/376a4835-7f9a-4b46-b197-8879743f505b)
![TimeAnalysis of Uber Trip Analysis](https://github.com/user-attachments/assets/a7401d58-ed64-4a13-8fe0-6a9a596199f2)
![DetailsofUber trip Analysis](https://github.com/user-attachments/assets/30e74107-3565-432c-90f9-21446c6ccde6)


# 🚗 Uber Trip Analysis – Power BI Dashboard

An interactive Power BI project built to analyze Uber ride data and deliver key insights on bookings, revenue, 
distance, time trends, and location patterns. This project supports business stakeholders in making data-driven 
decisions to optimize operations and customer experience.

---

## 📌 Problem Statement

To analyze Uber trip data and provide insights across various dimensions such as time, location,
vehicle type, and payment method. The goal is to support better planning, pricing, and resource 
allocation based on historical ride trends.

---

## 📊 Dashboards & Features

### 1. **Overview Dashboard**
- **KPIs:** Total Bookings, Total Booking Value, Average Booking Value, Total Trip Distance, Average Trip Distance, Average Trip Time
- **Dynamic Measure Selector:** Users can switch between key metrics (Bookings, Revenue, Distance)
- **Charts:** 
  - Total Bookings by Payment & Trip Type
  - Vehicle Type Analysis using matrix with conditional formatting
- **Location Analysis:**
  - Top Pickup & Drop-off Points
  - Farthest Trip
  - Total Bookings by Location
  - Most Preferred Vehicle by Pickup Location
- **Enhancements:** Dynamic Titles, Slicers, Clear Filters button, Data Detail Bookmarks

### 2. **Time Analysis Dashboard**
- **Visuals:**
  - Area Chart (Bookings by Pickup Time – 10-minute intervals)
  - Line Chart (Bookings by Day Name)
  - Heatmap (Bookings by Hour & Day of the Week)
- **Global Measure Control:** Dynamic selection across all charts

### 3. **Details Dashboard**
- **Grid Table:** Full trip data with drill-through
- **Bookmarks:** Toggle between filtered view and full dataset
- **User Actions:** Export raw data, view detailed trip records

---

## 🛠 Tools & Technologies Used

- Power BI Desktop  
- Power Query (Data Transformation)  
- DAX (Calculated Columns, Measures, Tables)  
- Excel (Structured Trip and Location Data)

---

## 🔍 Key Insights

- Identified peak ride times and frequent locations for pickups and drop-offs
- Tracked trip patterns across time, days, and vehicle types
- Enabled strategic decisions on pricing, fleet allocation, and customer preferences

---

## 🧠 How to Use:

1. Download the `.pbix` file
2. Open with Power BI Desktop
3. Use slicers, bookmarks, and dynamic selectors to explore data

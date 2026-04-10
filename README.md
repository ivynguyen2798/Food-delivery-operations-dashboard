# 🍔 Food Delivery Operations Dashboard

## 📌 Summary
This project presents an end-to-end operational analysis of a food delivery platform using Power BI. The dashboard provides insights into customer behavior, delivery performance, driver efficiency, and financial flows.

The analysis covers over **40,000 deliveries**, focusing on key metrics such as delivery time, tipping behavior, refund patterns, and demand trends across different locations and time periods.

---

## ⚙️ Key Tasks & Methodology

### 1. Data Preparation
- Cleaned and structured raw delivery data
- Built a **star schema model** (fact + dimension tables)
- Handled missing values and outliers

### 2. Feature Engineering
- Created key metrics:
  - GMV, Net GMV, Platform Revenue
  - Average Order Value (AOV)
  - Median End-to-End Delivery Time
  - On-time Rate
  - Tip %

### 3. Dashboard Development (Power BI)
- Designed **multi-page dashboard**:
  - Ops Overview
  - Customer Insights
  - Driver Performance
- Implemented:
  - Interactive slicers (area, tip, ASAP, time)
  - Drill-down and filtering
  - KPI cards and trend visuals

### 4. Analytical Techniques
- Time-series trend analysis
- Pareto analysis (refund concentration)
- Heatmap analysis (hour × day demand)
- Performance benchmarking (drivers & regions)
- Waterfall analysis for revenue flow

---

## 📊 Final Insights & Business Recommendations

### 🔍 Key Insights
- **Delivery speed directly impacts tipping behavior**
- Last-mile delivery accounts for **~45% of total delivery time**
- Demand peaks during **late-night hours**, requiring better driver allocation
- A small number of drivers/restaurants contribute to **most refunds (Pareto effect)**
- Driver performance varies significantly across key metrics

---

### 🚀 Business Recommendations

#### 1. Optimize Last-Mile Delivery
- Implement route optimization algorithms
- Use real-time traffic and location data

#### 2. Improve Driver Performance
- Introduce driver scoring system
- Provide incentives for high on-time rate & low refunds
- Identify and retrain underperforming drivers

#### 3. Demand-Based Driver Allocation
- Increase driver supply during peak hours (especially late-night)
- Apply surge pricing strategically

#### 4. Reduce Refunds
- Monitor high-risk restaurants and drivers
- Implement quality control mechanisms

#### 5. Enhance Customer Experience
- Focus on reducing delivery time variability
- Maintain consistent service quality to sustain tipping behavior

---

## 🛠 Tools Used
- Power BI
- DAX
- Data Modeling (Star Schema)
- Data Visualization

---

## 📁 Project Structure

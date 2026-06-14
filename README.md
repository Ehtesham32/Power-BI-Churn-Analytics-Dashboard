# Churn Analytics Dashboard (Power BI)

## 📌 Project Overview
This interactive Power BI dashboard provides a comprehensive analysis of customer churn dynamics, tracking key indicators like disconnections, reconnections, and overall net churn. Designed for business leaders, it delivers actionable insights into monthly operational trends, regional performance, and the primary drivers behind customer attrition for the year 2025.

![Churn Analytics Dashboard Preview](Churn%20Analytics%20Dashboard%20PowerBi.png)

---

## 🚀 Key Features & Insights

### 1. Executive Summary Cards
*   **Total Disconnections:** 22K overall account closures.
*   **Total Reconnections:** 4K successfully recovered accounts.
*   **Total Net Churn:** 18K net lost customer base.
*   **Operational Baselines:** Displays critical benchmarks with **Avg Disconnections (1867)**, **Avg Reconnections (363)**, and **Avg Net Churn (1503)** per month.

### 2. Time-Series Trend Analysis
*   **MoM Fluctuations:** Features a synchronized line-and-bar visual detailing operational performance across all 12 months.
*   **Peak Attrition Identification:** Clearly highlights **June** as the highest churn risk month with **2,668 disconnections** and a net loss spike of **2,288**.

### 3. Granular Performance Breakdown
*   **Reconnection Buckets:** Tracks how quickly users return. The vast majority of reconnections (**2,319**) occur within the critical **0-30 day window**, showing where retention efforts are most effective.
*   **Top Churn Drivers:** Identifies the root causes of customer loss, led heavily by **Permanent Disconnections (2,226)** and **Service Churn (1,208)**.
*   **Recon Types:** Segments the activation vectors, isolating **Direct Activations (38.72%)** and **Push initiatives (28.74%)** as core recovery channels.

---

## 🛠️ Tech Stack & Skills Demonstrated
*   **Tool:** Power BI Desktop
*   **Data Modeling:** Star Schema configuration linking operational metrics to time-intelligence tables.
*   **DAX Formulas:** Designed a dedicated "Key Metrics" table using advanced SWITCH logic to dynamically calculate and toggle core business metrics.
*   **UI/UX Design:** Implemented functional design choices including global slicing panels (Year, Branch), structured visual hierarchy, and cohesive corporate color anchoring.

---

## 📂 How to Interact with this Project
1. Clone or download this repository.
2. Ensure you have **Power BI Desktop** installed on your machine.
3. Open the `Churn_Analytics_Dashboard.pbix` file.
4. Use the slicing toggles at the top right to filter results seamlessly by **Year (2025/2026)** or **Branch Region (East, North, South, West)**.


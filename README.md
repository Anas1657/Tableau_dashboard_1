![Screenshot 2025-02-24 122429](https://github.com/user-attachments/assets/fab8c8d6-f174-482f-93d3-9a7230fac3f6)

# 📊 Daikibo Telemetry Data - Tableau Dashboard

## 📝 Project Overview
This project analyzes **telemetry data** collected from Daikibo’s **four factories** to identify:
1. **Which location had the most machine failures** (downtime analysis).
2. **Which machine types broke down the most** in that location.

An **interactive Tableau dashboard** was created to visualize insights and support data-driven decisions.

---

## 📂 Dataset Information
- **File Name:** `daikibo_telemetry_cleaned.csv`
- **Data Source:** Machine telemetry logs from **May 2021**.
- **Factories Covered:**
  - Daikibo Factory Meiyo (Tokyo, Japan)
  - Daikibo Factory Seiko (Osaka, Japan)
  - Daikibo Berlin (Germany)
  - Daikibo Shenzhen (China)
- **Key Columns:**
  - `factory` → Factory name
  - `deviceType` → Type of machine
  - `timestamp` → Time of recorded status
  - `status` → Machine condition (`healthy` / `unhealthy`)
  - `down_time` → Downtime in minutes (10 min per "unhealthy" status)

---

## 📊 Dashboard Visualizations
1. **Bar Chart: Down Time per Factory**
   - Displays total downtime (minutes) for each factory.
   - Helps identify the factory with the most breakdowns.
   
2. **Bar Chart: Down Time per Device Type**
   - Shows downtime per machine type.
   - Automatically filters based on the selected factory.
   
3. **Interactive Filtering**
   - Clicking on a factory **filters** the device downtime chart.
   - Enables **drill-down analysis** of machine failures.

---

## 🚀 How to Use the Dashboard
1. **Open Tableau Desktop** and import `daikibo_telemetry_cleaned.csv`.
2. Navigate to the **Dashboard** tab.
3. Click on a **factory bar** in the first chart to filter the second chart.
4. Analyze machine downtime trends and export insights.
5. Take a **screenshot** of the dashboard with the most affected factory selected.

---

## 📌 Conclusion
This Tableau dashboard provides actionable insights into **machine failures and factory downtime**, enabling better maintenance planning and operational efficiency at Daikibo.

---

## 🔗 Resources
- [Tableau Public](https://public.tableau.com/)
- [Daikibo Telemetry Data - CSV](daikibo_telemetry_cleaned.csv)

---

💡 *For any questions or improvements, feel free to reach out!* 🚀

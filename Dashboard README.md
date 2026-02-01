# Airline Flight Delay Analysis Dashboard ✈️

## 📌 Project Overview
This project focuses on analyzing airline flight delays using historical flight data and presenting key operational insights through an interactive dashboard. The dashboard helps identify delay patterns, contributing factors, and airline performance trends to support data-driven decision-making.

---

## 🎯 Objectives
- Analyze flight delay patterns across airlines, time periods, and airports
- Identify key contributors to flight delays
- Visualize performance metrics using interactive dashboards
- Provide actionable insights for improving airline punctuality

---

## 📊 Dataset
- **Source:** US Airline Flight Delay and Cancellation Dataset
- **Year Used:** 2018
- **Key Columns:**
  - `FL_DATE` – Flight date
  - `OP_CARRIER` – Airline carrier
  - `ORIGIN`, `DEST` – Airports
  - `DEP_DELAY` – Departure delay (minutes)
  - `DISTANCE` – Flight distance (miles)
  - `CANCELLED` – Cancellation indicator
  - Delay cause columns (`WEATHER_DELAY`, `CARRIER_DELAY`, etc.)

> A flight is considered **delayed** if the departure delay exceeds **15 minutes**.

---

## 🛠 Tools & Technologies
- **Power BI** – Interactive dashboard creation
- **Python (Pandas, Dask)** – Data preprocessing and analysis
- **Jupyter Notebook** – Exploratory analysis and documentation

---

## 📈 Key KPIs
- Total Flights
- Delayed Flights Count
- Delay Rate (%)
- Average Departure Delay (minutes)
- Average Flight Distance (miles)
- Cancellation Rate (%)

---

## 📊 Dashboard Features
- Delay distribution (Delayed vs On-Time)
- Average delay by airline
- Monthly delay trends
- Delay causes breakdown
- Airport-level delay analysis
- Interactive slicers (Airline, Month, Delay Status)

---

## 🔍 Key Insights
- Approximately one million flights experienced departure delays over 15 minutes.
- Certain airlines consistently show higher average delays.
- Delays increase during mid-year months, indicating seasonal congestion.
- Late aircraft and carrier-related issues are major contributors to delays.
- Evening flights tend to have higher delays due to delay propagation.

---

## 🧠 Conclusion
The Airline Flight Delay Analysis Dashboard provides a comprehensive view of operational performance across airlines and time periods. By identifying delay trends and root causes, the dashboard enables stakeholders to focus on targeted improvements to enhance on-time performance and customer satisfaction.

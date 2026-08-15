# ⚡ Electric Vehicle Dashboard

An interactive **Tableau dashboard** for exploring electric vehicle registrations by model year, state, manufacturer, vehicle type, model, and CAFV eligibility.

> **[🔗 View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/bhaskar.nakka4980/viz/EVDashboard_17866424745700/EvDashboard)**

![Electric Vehicle Dashboard](images/Ev%20Dashboard.png)

---

## 📊 Project Overview

This project analyzes electric vehicle registration data using Tableau to identify patterns across:

* Vehicle adoption by model year
* Geographic distribution by state
* Leading EV manufacturers
* BEV vs PHEV distribution
* CAFV eligibility
* Vehicle model-level registrations

The dashboard is designed to allow users to explore the data interactively rather than relying on static charts.

---

## 🎯 Business Objective

The goal of the dashboard is to provide a clear and interactive view of the EV population and help answer questions such as:

* How has EV registration changed across model years?
* Which states contain the most vehicles in the dataset?
* Which manufacturers account for the largest share of registrations?
* How are BEVs and PHEVs distributed?
* What proportion of vehicles falls into each CAFV eligibility category?
* Which vehicle models have the highest number of registrations?

---

## 🔑 Key Performance Indicators

| KPI                    |           Value |
| ---------------------- | --------------: |
| Total Vehicles         |     **150,413** |
| Average Electric Range | **67.83 miles** |
| Total BEV Vehicles     |     **116,745** |
| Total PHEV Vehicles    |      **33,668** |

---

## 📈 Dashboard Components

### 1. Vehicle Registrations by Model Year

A trend chart shows the number of registered vehicles across model years, allowing users to examine how registrations change over time.

### 2. Geographic Distribution

A U.S. map displays vehicle registrations by state, providing a geographic view of the dataset.

### 3. Top 10 Manufacturers

A ranked bar chart highlights the manufacturers with the highest number of registered vehicles.

### 4. CAFV Eligibility

A donut chart breaks down vehicles according to Clean Alternative Fuel Vehicle (CAFV) eligibility.

### 5. Vehicle Model Analysis

A detailed table provides model-level information including:

* Model
* Manufacturer
* EV type
* Total vehicles
* Percentage of total vehicles

---

## 🎛️ Interactive Filters

Users can dynamically filter the dashboard using:

* **CAFV Eligibility**
* **EV Type**
* **Model**
* **State**

The dashboard also supports hover-based exploration of charts and map data.

---

## 💡 Key Observations

Based on the dashboard:

* **BEVs represent the majority of vehicles**, with 116,745 registrations compared with 33,668 PHEVs.
* **Tesla has the largest manufacturer share** in the displayed dataset, accounting for more than half of the vehicles shown in the Top 10 manufacturer analysis.
* Vehicle registrations increase substantially across the later model years, with the highest point occurring around the 2023 model year in the displayed trend.
* The dataset is **strongly concentrated in Washington State**, so geographic findings should be interpreted as characteristics of this dataset rather than as a complete representation of nationwide EV adoption.

---

## 🗂️ Dataset

The project uses an electric vehicle population dataset containing vehicle-level attributes such as:

* VIN
* County
* City
* State
* Postal Code
* Model Year
* Make
* Model
* Electric Vehicle Type
* CAFV Eligibility
* Electric Range
* Base MSRP
* Legislative District
* Vehicle Location
* Electric Utility
* Census Tract

The original CSV is included in the repository for reproducibility.

---

## 🛠️ Tools & Technologies

* **Tableau** — Dashboard development and data visualization
* **CSV** — Data source
* **Git** — Version control
* **GitHub** — Project hosting and portfolio presentation

---

## 📁 Repository Structure

```text
EV Dashboard/
│
├── data/
│   └── Electric_Vehicle_Population_Data.csv
│
├── images/
│   └── Ev Dashboard.png
│
├── tableau/
│   └── EV Dashboard.twbx
│
├── .gitignore
└── README.md
```

---

## ⚠️ Data Scope & Limitations

This dashboard should not be interpreted as a complete statistical representation of the U.S. electric vehicle market.

The dataset has a strong geographic concentration, particularly in Washington State. Therefore:

* State comparisons should be interpreted within the dataset's coverage.
* Registration counts should not automatically be treated as total EV sales.
* The analysis describes the available dataset rather than the entire U.S. EV population.
* Dashboard results depend on the completeness and accuracy of the underlying dataset.

---

## 🔗 Project Links

**Interactive Tableau Dashboard:**
[View on Tableau Public](https://public.tableau.com/app/profile/bhaskar.nakka4980/viz/EVDashboard_17866424745700/EvDashboard)

**GitHub Repository:**
[View Source Files on GitHub](https://github.com/bhaskar-nb/ev-dashboard)

---

## 👤 Author

**Bhaskar**

Data Analyst Portfolio Project

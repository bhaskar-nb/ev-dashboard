# Electric Vehicle Dashboard

## Project Overview

An interactive Tableau dashboard analyzing electric vehicle adoption across the United States.

The dashboard explores EV registrations by model year, state, manufacturer, vehicle model, electric vehicle type, and Clean Alternative Fuel Vehicle (CAFV) eligibility.

## Business Objective

The objective of this dashboard is to provide an interactive view of the electric vehicle landscape and help users understand:

* How EV adoption has changed over time
* Which states have the highest number of registered EVs
* Which manufacturers dominate the EV market
* The distribution of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs)
* CAFV eligibility across registered vehicles
* Which vehicle models have the highest number of registrations

## Key KPIs

| KPI                    |       Value |
| ---------------------- | ----------: |
| Total Vehicles         |     150,413 |
| Average Electric Range | 67.83 miles |
| Total BEV Vehicles     |     116,745 |
| Total PHEV Vehicles    |      33,668 |

## Dashboard Features

### Vehicle Adoption Trend

The dashboard shows the number of registered electric vehicles by model year, allowing users to explore changes in EV adoption over time.

### Geographic Analysis

A state-level map shows the distribution of registered electric vehicles across the United States.

### Manufacturer Analysis

The Top 10 manufacturers visualization highlights the manufacturers with the largest share of registered vehicles.

### EV Type Analysis

The dashboard compares:

* Battery Electric Vehicles (BEV)
* Plug-in Hybrid Electric Vehicles (PHEV)

### CAFV Eligibility Analysis

The dashboard provides a breakdown of vehicles based on Clean Alternative Fuel Vehicle eligibility.

### Vehicle Model Analysis

A detailed table provides model-level information including manufacturer, EV type, vehicle count, and percentage contribution.

## Interactive Filters

Users can filter the dashboard using:

* CAFV Eligibility
* EV Type
* Model
* State

These filters allow users to drill down into specific segments of the EV market.

## Tools & Technologies

* Tableau
* Data Visualization
* Data Analysis
* CSV Dataset

## Dataset

The analysis uses the Electric Vehicle Population dataset containing vehicle-level information such as:

* VIN
* County
* City
* State
* Model Year
* Make
* Model
* Electric Vehicle Type
* CAFV Eligibility
* Electric Range
* Base MSRP
* Electric Utility
* Vehicle Location

The dataset is included in this repository for reproducibility.

## Dashboard Preview

![Electric Vehicle Dashboard](images/Ev%20Dashboard.png)

## Project Structure

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

## Tableau Dashboard

The interactive dashboard is available on Tableau Public.

**Tableau Public:** [View Interactive Dashboard](https://public.tableau.com/app/profile/bhaskar.nakka4980/viz/EVDashboard_17866424745700/EvDashboard)

## Key Takeaways

The dashboard provides an interactive way to examine EV adoption patterns across time, geography, manufacturers, vehicle types, and individual models.

The analysis shows a strong concentration of registrations among a small number of major manufacturers and provides a clear view of the relative distribution between BEVs and PHEVs.

## Author

**Bhaskar**

Data Analyst Portfolio Project

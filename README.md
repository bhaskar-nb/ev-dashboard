# Electric Vehicle Registration Analysis | Tableau

An interactive **Tableau dashboard analyzing electric vehicle registration records** across model years, states, manufacturers, vehicle types, models, and CAFV eligibility.

The project turns vehicle-level registration data into a business-style analytical view for exploring **EV adoption patterns, geographic concentration, manufacturer share, vehicle mix, and electric range**.

## Live dashboard

**[View the interactive dashboard on Tableau Public →](https://public.tableau.com/app/profile/bhaskar.nakka4980/viz/EVDashboard_17866424745700/EvDashboard)**

![Electric Vehicle Dashboard](images/Ev%20Dashboard.png)

## Project objectives

The dashboard is designed to answer questions such as:

- How does registration volume change across model years?
- Which states have the highest number of registered vehicles in the dataset?
- Which manufacturers and models have the largest representation?
- What is the mix of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs)?
- How is CAFV eligibility distributed?
- How does electric range vary across the vehicles represented?

## Key metrics

| Metric | Value |
|---|---:|
| Total vehicles | **150,413** |
| BEVs | **116,745** |
| PHEVs | **33,668** |
| Average electric range | **67.83 miles** |

> These figures describe the records included in the supplied dataset. They are not total U.S. EV sales or current EV-market figures.

## Key findings

- **BEVs represent the majority of records** in the dataset.
- **Tesla has the largest manufacturer share** among the records analyzed.
- Registration records are concentrated in later model years, with the highest displayed point around **2023**.
- The dataset has strong geographic concentration in **Washington State**, so geographic findings should be interpreted as characteristics of this dataset rather than a complete picture of U.S. EV adoption.

## Dashboard analysis

### Model-Year Trends
Explores how the number of registration records changes across vehicle model years.

### Geographic Distribution
Compares registration records by state and location to identify geographic concentration.

### Manufacturer & Model Analysis
Examines manufacturer share and model representation within the dataset.

### Vehicle-Type Mix
Compares **BEV** and **PHEV** records.

### CAFV Eligibility
Analyzes the distribution of Clean Alternative Fuel Vehicle eligibility categories.

### Electric Range
Explores the electric-range characteristics of the vehicles represented in the source data.

## Dataset

The project uses a vehicle-level **Electric Vehicle Population** dataset with fields including:

`VIN` · `County` · `City` · `State` · `Postal Code` · `Model Year` · `Make` · `Model` · `Electric Vehicle Type` · `CAFV Eligibility` · `Electric Range` · `Base MSRP` · `Legislative District` · `Vehicle Location` · `Electric Utility` · `Census Tract`

The source CSV is included in the repository for reproducibility.

## Tools & skills

- **Tableau** — dashboard development, visualization, filtering, and analysis
- **CSV** — source data
- **Git / GitHub** — version control and documentation

Skills demonstrated:

- EV / automotive data analysis
- Geographic analysis
- Trend analysis
- Manufacturer and product analysis
- KPI design
- Comparative analysis
- Interactive dashboard design
- Data storytelling
- Business intelligence

## Repository structure

```text
ev-dashboard/
├── data/
│   └── Electric_Vehicle_Population_Data.csv
├── images/
│   └── Ev Dashboard.png
├── tableau/
│   └── EV Dashboard.twbx
├── .gitignore
└── README.md
```

## Scope & limitations

This is a **portfolio analysis of the supplied EV registration dataset**. It should not be treated as a complete or current representation of the U.S. electric vehicle market.

- Registration records are not equivalent to total EV sales.
- The dataset has strong geographic concentration, particularly in Washington State.
- Conclusions depend on the completeness and accuracy of the underlying records.
- The dashboard is descriptive and does not provide EV-market forecasting or prediction.

## Author

**Bhaskar Nakka** — Data Analyst | SQL · Python · Tableau · Power BI

For opportunities or project discussions: **[bn7740401@gmail.com](mailto:bn7740401@gmail.com)**

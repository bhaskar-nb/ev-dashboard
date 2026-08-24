# Electric Vehicle Registration Analysis | Tableau

An interactive **Tableau dashboard analyzing electric vehicle registrations** across model years, states, manufacturers, vehicle types, models, and CAFV eligibility.

The project turns vehicle-level registration data into a business-style analytical view for exploring **EV adoption patterns, geographic concentration, manufacturer share, and vehicle mix**.

## Live dashboard

**[View the interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/bhaskar.nakka4980/viz/EVDashboard_17866424745700/EvDashboard)**

## Dashboard preview

![Electric Vehicle Dashboard](images/Ev%20Dashboard.png)

## What this project analyzes

- EV registrations by model year
- State-level geographic distribution
- Manufacturer and model share
- Battery Electric Vehicle (BEV) vs Plug-in Hybrid Electric Vehicle (PHEV) mix
- CAFV eligibility distribution
- Average electric range

## Key metrics

| Metric | Value |
|---|---:|
| Total vehicles | **150,413** |
| BEVs | **116,745** |
| PHEVs | **33,668** |
| Average electric range | **67.83 miles** |

These metrics describe the records included in the supplied dataset, not total U.S. EV sales or the current EV market.

## Key findings

- **BEVs make up the majority of records**, with 116,745 BEVs versus 33,668 PHEVs.
- **Tesla has the largest manufacturer share** in the dataset.
- Registrations are concentrated in later model years, with the highest displayed point around **2023**.
- The dataset is heavily concentrated in **Washington State**, so geographic conclusions should be interpreted as characteristics of this dataset rather than nationwide EV adoption.

## Business questions

The dashboard helps investigate:

- How does EV registration volume change by model year?
- Which states have the highest number of records?
- Which manufacturers and models dominate the dataset?
- What is the split between BEVs and PHEVs?
- How is CAFV eligibility distributed?
- How does electric range vary across the vehicles represented?

## Dataset

The project uses a vehicle-level **Electric Vehicle Population** dataset with fields including:

`VIN` · `County` · `City` · `State` · `Postal Code` · `Model Year` · `Make` · `Model` · `Electric Vehicle Type` · `CAFV Eligibility` · `Electric Range` · `Base MSRP` · `Legislative District` · `Vehicle Location` · `Electric Utility` · `Census Tract`

The source CSV is included in the repository for reproducibility.

## Tools

- **Tableau** — dashboard development and visual analysis
- **CSV** — source data
- **Git / GitHub** — version control and project documentation

## Skills demonstrated

- Data analysis
- Geographic analysis
- Trend analysis
- Comparative analysis
- KPI design
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

## Scope and limitations

This is a portfolio analysis of the supplied registration dataset. It should not be treated as a complete or current representation of the U.S. electric vehicle market.

- Registration counts are not equivalent to total EV sales.
- The dataset has strong geographic concentration, particularly in Washington State.
- Conclusions depend on the completeness and accuracy of the underlying records.

## Author

**Bhaskar Nakka** — Data Analyst | SQL · Python · Tableau · Power BI

For opportunities or project discussions: **[bn7740401@gmail.com](mailto:bn7740401@gmail.com)**

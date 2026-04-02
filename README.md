# Global Supply Chain Insights Dashboard

## Project Overview

This project was developed to analyze global trade patterns using an interactive Power BI dashboard. It focuses on supplier dependencies, import trends, and trade relationships across major economies.

The dashboard helps in understanding:

* Which countries dominate global supply chains
* How import dependency varies across economies
* How trade patterns changed over time (2019–2023)

---

## Objective

To analyze global import dependency and supplier concentration using trade data and provide clear, actionable insights through data visualization.

This project was built as part of my learning in data analytics and visualization, focusing on real-world supply chain problems.

---

## Country Selection Rationale

The analysis focuses on major global economies including USA, China, and Germany as primary importing countries, and China, Japan, Netherlands, and South Korea as key suppliers.

These countries were selected because:

* They represent the largest participants in global trade
* USA, China, and Germany are among the top importers globally
* China, Japan, Netherlands, and South Korea are major exporting economies
* Together, they form critical nodes in global supply chains

This selection ensures the analysis reflects real-world trade dependencies and global economic influence.

---

## Data Source

* UN Comtrade (International Trade Data)
* Dataset includes total import values across all commodity categories (HS TOTAL)

---

## Data Preparation & Filtering

The dataset was sourced from UN Comtrade and processed to focus on:

* Total imports (HS TOTAL category)
* Selected countries (major importers and suppliers)
* Time period: 2019–2023

Data cleaning steps included:

* Filtering relevant countries
* Aggregating total import values
* Removing incomplete or missing records
* Structuring data for visualization using Power BI and Excel

---

## Tools Used

* Microsoft Power BI
* Data Cleaning & Transformation using Power BI and Excel
* Data Visualization & Dashboard Design

---

## Key Features

### KPI Metrics

* Total Import Value
* Number of Importing Countries
* Number of Suppliers
* Average Import Value

### Interactive Filters

* Importer Selection
* Supplier Selection
* Year Range (2019–2023)

### Visualizations

* Import Dependency by Supplier (Stacked Bar)
* Trade Value Trend Over Time (Line Chart)
* Supplier Share Distribution (Donut Chart)
* Supplier Contribution by Importing Economy (Bar Chart)

---

## Key Insights

* China dominates global supplier share (~46%), indicating strong dependency
* USA records the highest import value (~3.8T), showing the largest demand
* Imports declined in 2020 due to the COVID-19 pandemic, followed by a gradual recovery by 2022, reflecting global supply chain disruption and resilience

---

## Analytical Focus

This dashboard demonstrates:

* Supply Chain Dependency Analysis
* Trade Distribution & Market Share
* Time-Series Trend Analysis
* Cross-country Comparison

---

## Analysis Modules

**Import Dependency**
Evaluation of supplier contribution across importing economies

**Supplier Share**
Distribution of total imports by supplier, highlighting dominant exporters

**Trade Trends**
Time-series analysis of import values from 2019 to 2023

**Country Comparison**
Comparison of sourcing patterns across USA, Germany, and China

---

## Note on Time Coverage

Some country-to-country trade relationships display different time ranges (e.g., Germany–China: 2019–2021, Germany–Japan: 2019–2022).

This variation is due to:

* Data availability differences in the source dataset
* Missing or incomplete records for certain country pairs
* Filtering applied to maintain data accuracy

Despite these variations, the analysis maintains consistency in identifying overall trade patterns and dependencies.

---

## Dashboard Preview

![USA Import](screenshots/usa_import_from_south_korea_2019_2023.png)

![Germany Import](screenshots/germany_import_from_china_2019_2021.png)

![China Import](screenshots/china_import_from_netherlands_2019_2023.png)


---

## Practical Applications

This project can be used for:

* Identifying supply chain risks and over-dependence on specific countries
* Supporting diversification strategies for imports
* Assisting policymakers in trade decision-making
* Helping businesses understand supplier concentration risks
* Analyzing global trade shifts during disruptions (e.g., COVID-19 period)

The dashboard provides a data-driven foundation for strategic supply chain planning.

---

## How to Use

1. Select an importing country (USA, China, Germany)
2. Filter suppliers to analyze dependency
3. Adjust year range to observe trade trends
4. Explore charts to compare supplier contributions

---

## Conclusion

The analysis highlights the dominance of key global suppliers and the varying dependency patterns across importing economies.
This project helped me better understand global trade dependencies and strengthened my skills in data visualization and analytical thinking.

---

## Author

Lakshaya S

---

## Project Type

Data Analytics | Business Intelligence | Supply Chain Analysis

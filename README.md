#  COVID-19 Data Analysis Using Power BI

### A Data Visualization Project by Chanchal

## Objective:

The goal of this project is to analyze the global impact of the COVID-19 pandemic using Power BI. The dashboard offers visual insights into total cases, deaths, vaccination progress, and trends over time — with the ability to filter by country or continent.

## 📁 **Data Source:**

* Dataset: OWID COVID-19 Data (Kaggle)
* Format: CSV
* Columns used:
  * `location`
  * `date`
  * `total_cases`
  * `new_cases`
  * `total_deaths`
  * `people_vaccinated`
  * `people_fully_vaccinated`
  * `continent`
  * 
## Tools Used:

* Microsoft **Power BI Desktop**
* DAX (Data Analysis Expressions) for custom calculations
* Power Query Editor (for data transformation)

## Main Visuals Created:

### 1. Line Chart – New Cases Over Time

* Shows trend of new COVID-19 cases by Year
* Helps track peak periods (e.g., second wave)

### 2. Bar Chart – Total Cases by Location

* Compares countries or regions based on confirmed total cases

### 3. Table – Vaccination Overview

* Lists countries with their vaccination numbers (people vaccinated & fully vaccinated)

### 4. Pie/Donut Chart – Total Cases by Continent

* Distribution of cases among continents

### 5. Card Visuals – KPI Metrics

* `Total Cases`
* `Total Deaths`
* `Death Rate (%)` → Custom DAX measure:

  ```DAX
  Death Rate (%) = DIVIDE(SUM(total_deaths), SUM(total_cases)) * 100

### 6. Slicer – Country Selection

* Allows users to filter entire dashboard by country for focused insights

## Insights Drawn:

* Death rate varies significantly across continents.
* Highest spikes occurred in late 2021 to early 2022.
* Some countries achieved near-full vaccination, visible in the vaccination table.

## How to Use:

1. Open the `.pbix` file in **Power BI Desktop**.
2. Use the **slicer** to select countries and explore their statistics.
3. Hover over charts for detailed tooltips.
4. Interact with visuals to analyze specific regions or timelines.

## Conclusion:

This Power BI dashboard enables real-time interactive analysis of the COVID-19 pandemic’s impact globally. It helps in **understanding trends, comparing locations**, and evaluating health response via **vaccination and fatality metrics**.



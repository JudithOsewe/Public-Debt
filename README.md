# Kenya Public Debt Analysis

## Project Overview

This project analyses Kenya's public debt trends from September 1999 to June 2026, focusing on the evolution of total public debt and the changing composition of domestic and external debt.

Using publicly available data from the Central Bank of Kenya (CBK), the project applies SQL, Python and data visualisation techniques to transform raw financial data into meaningful insights.

The objective is to demonstrate how data analytics can support better understanding of public finance, debt composition and long-term fiscal trends.

## Business Problem

Public debt is an important indicator of a country's fiscal position. However, raw financial data can be difficult to interpret without clear comparisons, trend analysis, and accessible visualisations.

This project seeks to answer the following questions:

- How has Kenya's total public debt changed over time?
- How has the composition of domestic and external debt evolved?
- What proportion of public debt comes from domestic versus external borrowing?
- How much has the nominal debt stock increased over the period analysed?
- How quickly has public debt grown over the period analysed?
- What trends can be observed in the structure of government borrowing?
- What do the findings suggest about the importance of monitoring public debt and debt servicing?

## Project Objectives

- Analyse historical public debt trends.
- Compare domestic and external debt.
- Examine changes in debt composition over time.
- Calculate key indicators and percentage changes.
- Identify patterns and notable changes in borrowing.
- Present findings through clear, decision-oriented visualisations.
- Demonstrate practical data analytics skills using real-world public finance data.

## Data Sources

The analysis uses publicly available data from official Kenyan government sources:

- [Central Bank of Kenya — Public Debt Statistics](https://www.centralbank.go.ke/public-debt/)
- [The National Treasury — Annual Public Debt Reports](https://www.treasury.go.ke/annual-debt-management-reports-0)
- [Public Debt Management Office](https://pdmo.treasury.go.ke/)

The final analysis will document the specific source, reporting period, units of measurement, and any data preparation applied.

**Dataset coverage:** September 1999 – June 2026
**Number of observations:** 316
*Main variables:*

- Year
- Month
- Domestic debt
- External debt
- Total public debt

**Unit of measurement:** KSh million.

The dataset contains observations of outstanding debt stock at different reporting periods. Reporting intervals are not uniform throughout the entire historical period.


## Tools and Technologies

Update this section to reflect the tools actually used.

- **pgAdmin 4:** Database administration and data import.
- **PostgreSQL:** Relational database storage and SQL-based analysis.
- **Python:** Data manipulation and exploratory data analysis.
- **Power BI:** Interactive dashboard development.
- **Pandas:** Data cleaning, transformation and calculations.
- **Matplotlib:** Data visualisation.
- **GitHub:** Version control, documentation and portfolio presentation.

## Methodology

1. **Data collection:** Obtain public debt data from official sources.
2. **Database Development:** Created a PostgreSQL database and a structured table to store the public debt dataset..
3. **Data Import and Validation:** Standardise reporting periods and distinguish domestic debt from external debt.
    Imported the dataset into PostgreSQL and performed validation checks, including:

      - Record count verification.
      
      - Duplicate reporting-period checks.
      
      - Month-range validation.
      
      - Non-negative debt value checks.
      
      - Reconciliation of total debt against domestic and external debt.

4. **Data Extraction:** Connected Python to PostgreSQL and extracted the data for exploratory analysis..
5. **Data Preparation:** Examine trends, growth rates, and changes in debt composition.                                          Used Pandas to prepare the dataset for analysis, including:
      -Creating a reporting date from the year and month fields.
      - Calculating domestic and external debt shares.
      - Preparing the dataset for trend analysis and visualisation.       
6. **Exploratory Data Analysis:** Examined historical debt trends, changes in debt composition and the growth of the outstanding debt stock.
7. **Exploratory Data Analysis:** Examined historical debt trends, changes in debt composition and the growth of the outstanding debt stock.
8. **Visualisation:** Developed charts to communicate the findings. Further visualisations and an interactive Power BI dashboard will be added as the project progresses.  


## Key Performance Indicators

The analysis focuses on the following indicators:
- Total public debt stock.
- Domestic debt stock.
- External debt stock.
- Domestic debt as a percentage of total debt.
- External debt as a percentage of total debt.
- Change in debt composition.
- Percentage growth in total recorded debt.

Additional indicators, such as debt-to-GDP and debt servicing ratios, may be incorporated where comparable supporting data is available.

## Preliminary Key Findings

The exploratory analysis of 316 observations covering September 1999 to June 2026 reveals the following:

### 1. Growth in Total Public Debt

Total recorded public debt increased from KSh 503,554.00 million in September 1999 to KSh 13,097,471.11 million in June 2026.
This represents a nominal increase of approximately 2,501.01% over the period.

### 2. Shift Towards Domestic Debt

Domestic debt increased from 36.42% of total public debt in September 1999 to 55.94% in June 2026.

This represents an increase of approximately 19.52 percentage points in the domestic debt share.

### 3. Declining External Debt Share

External debt declined from 63.58% of total public debt in September 1999 to 44.06% in June 2026.

This represents a decrease of approximately 19.52 percentage points.

### 4. Change in Debt Composition

The comparison between the first and last observations indicates a long-term shift in the composition of Kenya's outstanding public debt, from a larger external debt share towards a larger domestic debt share.

These findings describe changes in the outstanding debt stock and its composition. They do not independently establish the causes of borrowing, the amount of new borrowing in individual periods or the sustainability of public debt.





## Dashboard and Visualisations

Planned visualisations may include:

- Total public debt over time.
- Domestic versus external debt trends.
- Debt composition over time.
- Annual debt growth.
- Debt-to-GDP trends, where data is available.
- An interactive Power BI dashboard with key indicators and filters.


## Data Quality and Validation

Initial validation checks were performed on the imported dataset.

The checks confirmed:
- 316 records successfully imported.
- No duplicate year-month reporting periods.
- No invalid month values.
- No negative debt values.
- No discrepancies between total debt and the sum of domestic and external debt beyond the selected reconciliation tolerance.

Further validation will be performed as additional indicators and data sources are incorporated.

## Limitations

- The analysis is based on the historical dataset available at the time of collection and may not reflect subsequent revisions.
- Reporting intervals vary across the historical period; therefore, observations should not automatically be interpreted as equally spaced monthly records.
- Nominal debt growth does not account for inflation, changes in GDP or changes in the value of the Kenyan shilling.
- Exchange rate movements can influence the reported domestic-currency value of external debt.
- Debt composition alone does not establish whether the country's debt position is sustainable.
- Additional data is required to analyse debt servicing, revenue, GDP and other fiscal indicators comprehensively.

## Key Findings

This section will be updated after the data analysis is complete.

Findings will focus on measurable changes in public debt, shifts in debt composition, and other trends supported by the source data.

## Limitations

- Published figures may be revised by the relevant authorities.
- Different reports may use different reporting dates, definitions, or debt coverage.
- Nominal debt growth alone does not establish whether debt is sustainable.
- Findings describe observed patterns and should not be interpreted as proof of causation.

## Author

Data Analytics Portfolio Project

This project demonstrates practical skills in data preparation, exploratory analysis, financial data interpretation, and data visualisation.

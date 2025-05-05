# Maven Market

This project contains an interactive analytical dashboard created in Power BI, designed for in-depth analysis of key business metrics and visualization of data trends.

## Project Description

The goal of this project was to build a comprehensive tool in Power BI that allows for easy tracking and analysis of the most important operational/financial/sales key performance indicators **for Maven Market**. The dashboard enables quick identification of trends, comparison of data across different periods, and in-depth analysis at various levels of detail.

## Key Features and Dashboard Content

* **Interactive Visualizations:** A collection of various charts (line, bar), metric cards, tables, and slicers allowing for dynamic data analysis.
* **Key Metrics (Measures):** Presentation and analysis of essential indicators such as:
    * Revenue
    * Profit
    * Sales Quantity
    * Cost
    * Average values (e.g., Average Revenue per Transaction)
    * Period-over-Period comparisons (e.g., Year-over-Year, Month-over-Month - if included)
    * ETC. (The complete list of DAX measures used in this analysis is available within the Power BI file.)
* **Data Filtering:** Ability to filter data by date, category, region, etc., allowing for analysis of specific data subsets.

## Technical Aspects

* **Data Modeling:** Preparation of a data model connecting different source tables to enable comprehensive analysis.
* **DAX Measures:** **All key metrics and calculations (measures)** were created using the **DAX** language.
* **Data Transformation (Power Query):** Data processing and cleaning operations were performed in **Power Query**, including [e.g., adding several columns, changing data types, filtering rows] to prepare the data for modeling and analysis.
* **Visualization Design:** Comprehensive design and implementation of all visual elements of the dashboard to ensure clarity and usability.

## Repository Contents

* `MavenMarket_Report.pbix`: The main Power BI project file containing the data model, DAX measures, Power Query queries, and visualizations.
* `README.md`: This file describing the project.

## How to View the Dashboard

1.  Clone or download the repository.
2.  Open the `MavenMarket_Report.pbix` file using Power BI Desktop.

## Screenshots

![image](https://github.com/user-attachments/assets/61fde6e4-ac48-4382-a795-fb25e405f6fa)
![image](https://github.com/user-attachments/assets/48e18010-e8a5-4cab-8503-0d2040d7a267)


---

This project was completed as a final project for the Udemy course: [Microsoft Power BI: Up & Running With Power BI Desktop](https://www.udemy.com/course/microsoft-power-bi-up-running-with-power-bi-desktop/)

# Inside-Airbnb-Toronto

## Objective 
Provide a Power BI report that examines the Airbnb market in Toronto, 
offering valuable insights for investors looking to enter the short-term rental market.

## Technical Details

### ETL Process

- **Data Extraction:**
  - Nine CSV files were imported: listings, neighborhoods, and reviews tables for Q2, Q3, and Q4 of 2023.
- **Data Cleaning and Transformation (Power Query)**:
  - Concatenated the Q2, Q3, and Q4 Tables.
  - Addressed data quality issues such as incorrect data types and duplicate records.
  - Selected relevant columns for analysis.
  - Split columns and created new columns and tables.
- **Data Modeling (Model View):**
  - Implemented a star schema data model to improve data consistency and query performance.

### Report

- Created several interactive visualizations to implement storytelling techniques.
- Implementation of filter panel for a dynamic presentaion.
- Successfuly implemented DAX for measures and table creation.

## Documentation

You can see the project documentation here.

## Impact

Identified a potential 25% increase in rental prices, offering strategic recommendations on optimal 
locations and rental types, directly supporting stakeholder decision-making.

## Visuals

Line chart, key influencers, slicer, heat map, table, matrix, bar chart, and pie chart.


## Disclaimer
This report is provided for educational purposes only. The information, analyses, and opinions contained herein are based on public data available in [insideairbnb.com](https://insideairbnb.com/get-the-data) about rental prices in 2023.

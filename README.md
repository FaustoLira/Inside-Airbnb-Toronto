# Inside-Airbnb-Toronto

## Introduction

This Power BI presentation examines the Airbnb market in Toronto, offering valuable insights that can benefit investors looking to enter the short-term rental market. Toronto, recognized as one of North America's most vibrant and culturally diverse cities, presents great opportunities for investors in the short-term rental market. The city is also a favorite destination for millions of tourists every year.

**Disclaimer**
This report is provided for educational purposes only. The information, analyses, and opinions contained herein are based on public data available in [insideairbnb.com](https://insideairbnb.com/get-the-data) about rental prices in 2023.

## Insights and Recommendations

**Insight 1: Strategic Acquisition**  
Starting from the 'Expected Revenue' page, the average rental price has been on an uptrend since 2010. The analysis shows that **the average rental price could be around $250 in 2028, corresponding to a 25% rental price increase**. However, the price is in a downtrend in the short term, indicating a possible opportunity for buying.

**Insight 2: Best Locations**  
The 'Key Influencers' chart on the 'Expected Rental Price' page lists the most important factors for price growth. **Rental prices in Waterfront Communities strongly impact the increase in rental prices in Toronto**. On the 'Best Location' page, all the metrics indicate that the area around Waterfront Communities Island Neighborhood is vital to rental price growth.

**Insight 3: Characteristics of a “Good” Unit to Invest In**  
On the ‘Unit Type’ page, you can see that traditional accommodations, including houses and condos, account for 88% of all rental units listed on Airbnb. **Investing in underpriced traditional accommodations in the Waterfront Communities Island could be a great business opportunity.**

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


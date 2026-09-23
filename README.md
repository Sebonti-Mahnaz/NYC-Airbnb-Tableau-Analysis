# NYC Airbnb Tableau Analysis

## Project Overview
This Tableau capstone project analyzes the NYC Airbnb market to understand how location, pricing, room type, minimum-night requirements, availability, and review activity shape market behavior across New York City.

The project combines seven worksheets, three interactive dashboards, and a five-part Tableau story to examine the contrast between premium and budget markets, identify neighborhood-level patterns, and explore how pricing and booking rules relate to guest engagement.

## Dataset
The analysis uses a cleaned NYC Airbnb dataset with listing and host information, neighborhood location, room type, price, minimum nights, reviews, review dates, host listing counts, and annual availability.

## Data Preparation
- Removed null values from `last_review` in Excel.
- Applied a **$10–$2,000** price filter to reduce invalid values and extreme outliers.
- Defined the premium price range as **$200–$2,000**.
- Grouped minimum nights into **Short Stay (1–5 nights)**, **Medium Stay (6–30 nights)**, and **Long Stay (31+ nights)**.
- Defined premium neighborhoods in Tableau using average price.
- Restricted trend analysis to post-November 2015 to reduce noise from earlier records.

## Tableau Worksheets
1. **Listings by Location and Price** — Geographic map of listings and pricing categories.
2. **Price According to Neighbourhood Groups** — Average-price comparison across boroughs.
3. **Top 3 Neighbourhoods by Metric Selector** — Interactive comparison across selectable metrics.
4. **Neighbourhood vs. Room Type Comparison** — Heat map of room-type concentration.
5. **Distribution in Premium vs. Outer Neighbourhoods** — Box plot comparing price distributions and medians.
6. **Review Trends Over Time** — Monthly review trends.
7. **Price vs. Number of Reviews by Minimum Night** — Scatter plot connecting price, reviews, and minimum-night groups.

## Dashboards

### 1. Premium Neighborhood Pricing Insights
Combines the location map and average-price comparison to show how geography and pricing interact.

### 2. Pricing Intensity and Distribution — Premium vs. Outer
Combines a heat map and box plot to compare listing concentration, room types, price spread, and median pricing.

### 3. Reviews & Engagement by Price and Minimum Night
Combines review trends with a price-versus-reviews scatter plot to explore how pricing and minimum-night policies relate to engagement.

## Key Insights
- Manhattan and Brooklyn show strong premium pricing patterns.
- Queens performs as a comparatively consistent mid-market area across several metrics.
- Bronx and Staten Island provide affordable market segments and show strength in selected review and availability measures.
- Entire homes and private rooms drive higher prices and review activity, while shared rooms remain the budget option.
- Review activity rises strongly after 2015 in the filtered analysis period.
- Shorter minimum-night requirements show stronger review engagement than longer stays.
- Neighborhoods leading in supply and pricing are not always the same areas that stand out in reviews or availability.

## Business Recommendations
- Position Manhattan and Brooklyn toward premium and luxury demand while maintaining flexible minimum-night requirements.
- Market Queens as a balanced mid-market option.
- Highlight affordability in Bronx and Staten Island to broaden market reach.
- Use minimum-night policies strategically to support guest engagement.

## Tools Used
- **Tableau Desktop** — Visualizations, dashboards, filters, parameters, groups, sets, calculated fields, aggregations, dashboard actions, and storytelling
- **Microsoft Excel** — Data cleaning and preparation
- **Power BI** — Used during data checking to help identify and resolve data issues

## Project Structure
The portfolio repository is designed to include the packaged Tableau workbook, cleaned Airbnb dataset, and supporting project documentation alongside this README.

## Skills Demonstrated
Data cleaning · Exploratory data analysis · Tableau calculations · Interactive filters and parameters · Dashboard design · Geographic analysis · Data storytelling · Business insight generation

## Author
**Sebonti Mahnaz**

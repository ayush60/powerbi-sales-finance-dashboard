
 Sales & Finance Analysis Dashboard — Power BI Portfolio Project

## Short Description / Purpose
An interactive Power BI dashboard built on publicly available sample datasets 
(Sample Superstore, Finance Sample) to practice and demonstrate an end-to-end 
BI workflow — data modeling, DAX measures, and interactive dashboard design. 
Built as a portfolio project to apply and showcase Power BI skills as a 
fresher Data Analyst.

## Tech Stack
- Power BI Desktop
- DAX (YOY % measures, running totals, category-wise breakdowns)
- Power Query (data cleaning, transformation, date tables)
- Bookmarks & Selection Pane (interactive page navigation)

## Data Source
- Sample Superstore — publicly available retail order-level dataset 
  (Category, Sub-Category, Sales, Profit, Quantity, Discount, Region, Segment),2014–2017
- Finance Sample — publicly available finance dataset by segment/country 
  (Units Sold, Gross Sales, COGS, Discounts, Profit), 2013–2014

Both are widely used public/training datasets, not proprietary or client data.

## Features / Highlights

 Business Problem
This project simulates a common analytics scenario: transactional data spread across orders, segments, and
time periods, with no single view to answer basic questions like — which categories drive sales,
is profit growing or shrinking year over year, and which segments or regions are most profitable. 
As this is a portfolio project on sample data, the "business problem" is a practice scenario rather than 
a real client's — the goal was to build the kind of dashboard a retail or finance team would actually use.

 Goal of the Dashboard
- Track sales and profit trends year-over-year
- Break down performance by category, sub-category, country, and segment
- Enable drilling from Year → Quarter → Month within a single page (via bookmarks) instead of multiple report pages
- Surface under/over-performing sub-categories at a glance using conditional formatting

 Walkthrough of Key Visuals
- Finance Overview — KPI cards (Total Profit, Units Sold, Gross Sales) with a year slicer; profit-by-country donut
  and profit-by-segment funnel chart show where profit concentrates
- Sales Waterfall — shows how each category (Furniture, Office Supplies,Technology) and year adds to or 
  subtracts from total sales, ending at a cumulative ~836K
- YOY Growth Trend — combo chart comparing current year vs previous year sales bars with a YOY % line overlay
- Bookmark Navigation — three bookmarks (Year, Quarter, Month) swap the same chart's granularity via 
  the Selection pane, avoiding separate report pages
- Conditional Formatting Table — sub-category table using a color scale (Sales), data bars (Quantity), and 
  up/down icons (Profit trend) to surface outliers instantly

Business Impact & Insight
Observations drawn directly from the sample data used in this project — not outcomes from a real 
business engagement, since this is a practice dataset, not live company data.
- Technology is the largest contributor to total sales (~836K cumulative in 
  the waterfall view), while Office Supplies shows a net decrease in the 2015–2016 period
- 2016 shows the highest YOY growth at 29.47%, compared to 20.36% in 2017
- Tables and Bookcases are the only sub-categories with negative profit despite non-trivial sales 
  volume, visible directly in the conditional formatting table
- In the Finance dataset, the Government segment holds the largest profit share (11.39M),
  while Enterprise shows a net loss (-0.61M)

Screenshots / Demos
![Dashboard Demo](screenshots/dashboard-demo.gif)
![Finance Dashboard](screenshots/finance-dashboard.jpg)
![Sales Waterfall](screenshots/waterfall-chart.jpg)
![YOY Growth](screenshots/yoy-growth.jpg)
![Bookmark Navigation](screenshots/bookmarks-navigation.jpg)
![Conditional Formatting](screenshots/subcategory-table.jpg)

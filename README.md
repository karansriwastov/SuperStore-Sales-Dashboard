# SuperStore Sales & Forecasting Dashboard

A dynamic Power BI project designed to track retail performance across the US and use data-driven forecasting to predict future sales trends.

![SuperStore Sales Dashboard](Dhasboard.jpg)

## Overview

I built this multi-page dashboard to solve a common retail problem: turning messy sales logs into actual business strategy. The first page acts as a command center for historical tracking—breaking down $1.57M in sales and $175K in profit. The second page focuses entirely on the future, leveraging time series analysis to project a 1-month sales forecast so managers can make smarter inventory decisions.

##  Tech Stack
* Power BI Desktop – Dashboard design and data visualization.
* Power Query – ETL process (cleaning, transforming, and reshaping the raw data).
* DAX – Writing custom measures, KPIs, and time-intelligence logic.
* Power BI Forecasting Engine – Running the time series models.

## Data Source

* Dataset: US Superstore Dataset (Transactional retail data tracking orders, categories, regions, and shipping).

## Key Features

### 1. Business Performance Tracking (Page 1)

* At-a-Glance KPIs: High-level cards for quick insights into total sales ($1.57M), profit ($175.26K), product volume (22K items), and an average shipping delay of 4 days.
* Sales Breakdown: Interactive charts slicing data by customer segment (Consumers lead at 48%), region (West leads at 33%), and payment type (COD is most popular at 43%).
* Product Insights: Tracks sales by category, showing that Office Supplies generated the highest volume ($0.64M), with Phones being the top-selling sub-category ($0.20M).
* Geographical Map: A map visualization to quickly spot high-profit hubs and low-performing states.

### 2. Time Series Forecasting (Page 2)

* 1-Month Sales Forecast: A built-in predictive model projecting upcoming sales trends with a shaded confidence interval.
* Interactive Slicers: A timeline slider that lets users zoom into specific months (like Sep 2020 – Jan 2021) to look closely at seasonal sales spikes.
* State Rankings: Displays top revenue-driving states, led by California ($0.34M) and New York ($0.19M), to align forecasts with geographic scale.

## Key Business Takeaways

* Fix Shipping Bottlenecks: Spotting the 4-day average shipping buffer gives logistics teams a clear benchmark to optimize delivery speeds.
* Smart Stocking: By using the 1-month forecast, inventory managers can anticipate seasonal demand spikes, reducing both stockouts and wasteful overstocking.
* Targeted Marketing: Knowing exactly which sub-categories (like Phones) and states (like California) bring in the most margin helps teams allocate ad spend where it actually converts.

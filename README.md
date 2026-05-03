# Opportunity-Dashboard
This dashboard provides a simple overview of sales opportunities, revenue, and performance. It helps track deal progress and identify trends across industries.

🔑 Key Features
Overview of total opportunities, revenue, win rate, and loss rate
Revenue analysis by industry
Trends of closed won vs closed lost deals over time
Win rate vs loss rate comparison by industry
Sales pipeline breakdown by stage

Filters
Year & Quarter
Industry
Stage

Tools & Technologies
Excel (data source)
Power BI (dashboard creation)
DAX (calculated measures and KPIs)
  DAX Measures (Sample)

- Win Rate = DIVIDE([Closed Won], [Total Opportunities], 0)

- Loss Rate = DIVIDE([Closed Lost], [Total Opportunities], 0)

- Avg Revenue = AVERAGE(Opportunities[Revenue])

- Avg Days to Close = AVERAGE(Opportunities[Days to Close])

🎯 Purpose
To help teams monitor sales performance, analyze the pipeline, and make better business decisions.

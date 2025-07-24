Delivery Delay Analysis

This project analyzes delivery performance using a dataset of over 10,000 shipments. It explores the relationship between shipment methods, delays, product characteristics, and cost using Python, SQL, and Power BI.

Files
train.csv – Raw dataset used for analysis

delivery_delay_analysis.ipynb – Python notebook for cleaning, EDA, and summary statistics

delivery_delay_queries.sql – SQL scripts to answer key analytical questions

delivery_delay_analysis.pbix – Power BI dashboard with interactive visuals

README.md – Summary and documentation of the project

Key Questions Explored
Which shipment mode is used most frequently?

Are heavier products more likely to be delayed?

How do costs vary across shipment methods?

What is the distribution of product importance?

How do delays correlate with product characteristics?

Tools Used
Python (Pandas, Matplotlib) for data exploration and cleaning

SQL (SQLite) for grouped summaries and aggregation

Power BI for dashboard creation and visualization

Summary of Insights
Shipments by Ship mode are most common, followed by Road and Flight

Average product cost is similar across all shipment modes (roughly $209–$210)

On-time shipments tend to weigh more than delayed ones

Most shipments are of low or medium importance

Discount levels are fairly consistent across warehouse blocks

Power BI Dashboard
The dashboard includes the following visuals:

Deliveries by Shipment Mode

Avg Discount by Warehouse Block

Average Product Cost by Shipment Mode

Product Importance Share

Delayed vs On-Time (pie chart)

Shipment Mode vs Delivery Status (stacked bar)

A slicer to filter all visuals by Mode of Shipment


# Supply Chain & Logistics Dashboard

## Overview
An interactive 3-page Power BI dashboard analysing 180K+ 
supply chain records tracking KPIs like on-time delivery 
rate, late orders and profit margin across global operations.

## Tools Used
- Python (Pandas) — data cleaning & feature engineering
- Power BI — dashboard development & visualisation

## Dataset
Source: DataCo Supply Chain Dataset

Platform: Kaggle

Link: https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis

Download the dataset from the link above and run 
`supply_chain_cleaning.ipynb` to generate the clean CSV.

Original csv file from Kaggle couldn't be uploaded beacues of the file size limit.

## Key Insights
- On-time delivery rate of 42.7% across all regions
- Central Africa has highest late delivery rate at 60.70%
- Golf Bags & Carts is most profitable category at 17.46%
- Standard Class handles 60% of all shipments

## Dashboard Pages
- **Overview** — KPIs, monthly trend, delivery status
- **Delivery Analysis** — regional analysis, heatmap, trend
- **Geo & Category** — world map, profit by category

## Files
- `Supply_Chain_Dashboard.pbix` — Power BI file
- `Supply_Chain_Dashboard.pdf` — Dashboard export
- `supply_chain_cleaning.ipynb` — Python cleaning notebook
- `supplychain_clean.csv` — Cleaned dataset

Grivy Technical Test - Campaign Performance Analysis

This project loads three input data sources:
- transactions
- campaigns
- metrics

The script performs SQL-like joins using DuckDB in Python, calculates campaign performance metrics (CPC, ROI, Bounce Rate), and simulates engagement trends over time for Campaign 301.

It also generates the following plots:
- Engagement trends over time (clicks, impressions, landing hits)
- Customer segment comparison by average transaction size
- Product category sales distribution (pie chart)

All results are saved locally as PNG files.

To run:
1. Install required packages: pandas, matplotlib, numpy, duckdb
2. Run the script in a Python environment
3. Make sure the CSV or DataFrame sources are correctly loaded if not using mock data

This test assumes basic campaign analytics logic, such as prorating, grouping, and plotting for business insight.
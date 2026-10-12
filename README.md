# Power-BI---Maven-Market-Report-Project
Maven Market – Topline Performance Dashboard (Power BI)
Power BI report for Maven Market, a fictional grocery chain with stores in Canada, Mexico and the USA. Built as a practice project on the Maven Analytics dataset (transactions from Jan 1997 to Dec 1998).

What I Built:
Data prep (Power Query): imported 7 CSV tables (customers, products, stores, regions, calendar, transactions, returns), fixed data types, added derived columns, and combined the yearly transaction files.
Data model: star schema with a snowflake link (Stores to Regions), one-to-many one-way relationships, and an inactive date relationship for stock date.
DAX: calculated columns and measures for revenue, cost, profit, margin, return rate, YTD revenue, 60-day running total, last-month comparisons and a revenue target
Report: matrix with data bars and colour scales, KPI cards, map, drill-down treemap, gauge, slicers, and bookmarks with a Notes page linking to key insights

Headline Numbers:
269,720 transactions · $1.76M revenue · $1.05M profit · 59.7% profit margin · 0.99% return rate · 28.4% weekend transactions

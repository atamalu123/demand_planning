# Demand Forecasting and Planning

This Excel analysis takes 24 month of historical data from 2 different SKUs (items) and: 

1. Performs demand forecasting for both items (tests different forecasts and picks the best ones).
2. Calculates standard inventory planning metrics such as Safety Stock, Economic Order Quantity (EOQ), Reorder Point (ROP) for both items.

# Sheets

1. Historical Data - Contains the original data and added columns required to calculate demand forecasts, forecast accuracy, and inventory metrics.
2. Data Summary - A high-level overview of the data.
3. 12-Month Demand Forecast - 12 months of demand forecast data past the last month in the data. Uses the optimal forecast for each item.
4. Inventory Planning - Calculations relevant to planning, such as Safety Stock, EOQ, and ROP.
5. Forecast Accuracy - The accuracy of each demand forecast performed for each item (uses MAPE).

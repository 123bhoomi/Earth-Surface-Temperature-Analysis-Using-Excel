# Earth-Surface-Temperature-Analysis-Using-Excel
Analyzed Earth surface temperature data (land and ocean) using Excel to explore climate change patterns, calculate anomalies, and build an interactive dashboard with advanced Excel features and visualizations.

Task 1:
Data Cleaning And Preprocessing:
1.Convert the dt column to Excel DATE format for consistent time-series analysis.
2.Check for and highlight any missing or blank temperature values in all temperature columns using ISBLANK() or COUNTBLANK().
3.Ensure all temperature columns (including uncertainties) are in numeric format with two decimal places; identify and fix any non-numeric entries.
4.Standardize column headers using the PROPER() function if they have inconsistent capitalization.

Task 2:
Data Analysis And Calculations:
1.Calculate the monthly average of LandAverageTemperature for each year using AVERAGEIFS().
2.Calculate the yearly average of LandAndOceanAverageTemperature.
3.Compute the temperature anomaly for each year relative to the 1850–1900 baseline average (as a pre-industrial reference).
4.Identify the top 10 hottest years based on LandAndOceanAverageTemperature.

Task 3:
Advanced Excel Concepts:
1.Dropdown Filter: Create a dropdown list to select a year and display all monthly temperatures for that year.
2.VLOOKUP() Or INDEX/MATCH: Build a lookup tool to fetch all temperature stats for a selected month/year.
3.Pivot Table: Year in rows, Average LandAverageTemperature and LandAndOceanAverageTemperature in values and Temperature Type (Land VS LandAndOcean) in filters.
4.Conditional Formatting: Highlight temperatures exceeding 1.5 °C anomaly in red and shade any months with missing temperature values in yellow.

Task 4:
Visualization And Dashboard:
1.Line Chart: Plot the LandAndOceanAverageTemperature over time to show long-term warming trends.
2.Bar Chart: Compare average temperatures by decade.
3.Pie Chart: Visualize the share of months with anomalies above 1.5 °C.
4.Slicer: Add interactive slicers to filter data by Year and Temperature Type (Land VS LandAndOcean).


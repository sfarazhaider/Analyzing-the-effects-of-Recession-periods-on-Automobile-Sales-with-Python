# Analyzing the effects of Recession periods on the Automobile Sales with Python

**Scenario**

The goal of this project is to create plots and visualizations to analyze "historical_automobile_sales" data to understand the historical trends in automobile sales during recession periods.
recession period 1 - year 1980
recession period 2 - year 1981 to 1982
recession period 3 - year 1991
recession period 4 - year 2000 to 2001
recession period 5 - year end 2007 to mid 2009
recession period 6 - year 2020 -Feb to April (Covid-19 Impact)

**Data Source**

The data is taken from the IBM course series for Data Analysis
https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/historical_automobile_sales.csv

**Data Description**
The dataset used for this visualization assignment contains historical_automobile_sales data representing automobile sales and related variables during recession and non-recession period.

The dataset includes the following variables:
1. Date: The date of the observation.
2. Recession: A binary variable indicating recession perion; 1 means it was recession, 0 means it was normal.
3. Automobile_Sales: The number of vehicles sold during the period.
4. GDP: The per capita GDP value in USD.
5. Unemployment_Rate: The monthly unemployment rate.
6. Consumer_Confidence: A synthetic index representing consumer confidence, which can impact consumer spending and automobile purchases.
7. Seasonality_Weight: The weight representing the seasonality effect on automobile sales during the period.
8. Price: The average vehicle price during the period.
9. Advertising_Expenditure: The advertising expenditure of the company.
10.Vehicle_Type: The type of vehicles sold; Supperminicar, Smallfamiliycar, Mediumfamilycar, Executivecar, Sports.
11.Competition: The measure of competition in the market, such as the number of competitors or market share of major manufacturers.
12.Month: Month of the observation extracted from Date..
13.Year: Year of the observation extracted from Date.
By examining various factors mentioned above from the dataset, we aim to gain insights into how recessions impacted automobile sales.

-Plotted yearly automobile sales trends with Pandas to show how sales fluctuated over time.
-Compared sales trends by vehicle type across recession and non-recession periods, using line plots and Seaborn.
-Used subplots to compare GDP variation in recession and non-recession periods.
-Built a bubble plot to show how seasonality affects sales.
-Built a Matplotlib scatter plot to test whether average vehicle price was correlated with sales volume during recessions.
-Used pie charts to break down advertising spend by period (recession vs non-recession) and by vehicle type during the recession.
-Used a count plot to analyse how the unemployment rate affected sales by vehicle type during the recession.
-Mapped the highest-sales regions and offices during the recession.


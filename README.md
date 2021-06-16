# Coronavirus and its impact on unemployment rate

List of requirements needed in order to recreate these report is listed in requirements.txt file.

This project is an automated report on coronavirus and its impact on unemployment rate. \
The report shows current coronavirus situation (it is scraped automatically from Wikipedia page: https://en.m.wikipedia.org/wiki/COVID-19_pandemic_by_country_and_territory# ). \
As the main examined problem is unemployment situation the report shows 1 year change in OECD countries, situation in G7 countries and Poland's unemployment rate in comparison to European Union countries.\
These data comes from OECD site: https://data.oecd.org/unemp/unemployment-rate.htm \
Report shows analysis based on the input data which comes from OECD site. 

The next part of report is concentrated on country-specific unemployment rate. One can chose a country and get different graphs for analysis.  \
The first one is interacted graph which shows unemployment by gender. One can chose any time period for analysis \
The next ones shows unemployment by education level and age for chosen country  \
The last part of report is concentrated on forecasting unemployment rate. One can see the results of different tests and ARIMA parameters,which are chosen automatically. At the end ARIMA with best parameters are shown (two approaches are used). 

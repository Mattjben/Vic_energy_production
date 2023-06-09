
# Time Series analysis: Energy Demand Forecast Victoria 


**Research Question:** What are the most accurate forecasts for monthly averaged total daily electricity demand in Victoria for the next 10 months? 


With the resurrection of the State Electricity Commission (SEC), announcement of offshore wind farms in southeast Victoria and Victoria’s renewable energy target of 50% by 2030 , being able to accurately predict energy demand on a continual basis is becoming increasingly important. As renewable energy sources like wind and solar do not produce constant energy outputs, accurate forecasting of energy demand throughout the day is essential to ensure renewable energy sources are used efficiently. Demand forecasting has become increasingly relevant when incorporating renewable into the grid and in general reduces over and underproduction of energy and minimises energy waste as a whole.

**Data Source**:https://www.kaggle.com/datasets/aramacus/electricity-demand-in-victoria-australia

This data set contains the total daily energy demand across Victoria in MWh from 1st Jan 2015 to 6 Oct 2020 which consists of 2016 days. Although the additional features of this data set may not be directly relevant to this report, below is a list of variables contained in the data and their description:

•	date: datetime, the date of the recording. 
•	demand: float, a total daily electricity demand in MWh. 
•	RRP: float, a recommended retail price in AUD$ / MWh. 
•	demand_pos_RRP: float, a total daily demand at positive RRP in MWh. 
•	RRP_positive: float, an averaged positive RRP, weighted by the corresponding intraday demand in AUD$ / MWh. 
•	demand_neg_RRP: float, a total daily demand at negative RRP in MWh. 
•	RRP_negative: float, an average negative RRP, weighted by the corresponding intraday demand in AUD$ / MWh. 
•	frac_at_neg_RRP: float, a fraction of the day when the demand was traded at negative RRP. 
•	min_temperature: float, minimum temperature during the day in Celsius. 
•	max_temperature: float, maximum temperature during the day in Celsius. 
•	solar_exposure: float, total daily sunlight energy in MJ/m^2. 
•	rainfall: float, daily rainfall in mm. 
•	school day: boolean if students were at school on that day. 
•	holiday: boolean if the day was a state or national holiday. 
Note: All code provided is written in Rstudio using R 4.2.0 

# FILE LOCATIONS

- **R Code**: all R markdown project code used to test and analyse possible time series models 
- **Report**: Final report of time series forecast 
- **Presentation**: presentation on intial findings of report

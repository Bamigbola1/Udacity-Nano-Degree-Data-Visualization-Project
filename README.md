# (Exploration of Flight Dataset)
## by (BAMIGBOLA VICTOR)


## Dataset

> The dataset is from Data Expo 2009. It comprises of flight operation details i.e Arrival and Departure of all flight within USA, starting from October 1987 to April 2008. We have the dataset divided into each year which can be downloaded on there website. There website address is as follows https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7. However, for the sake of this analysis we would limit the dataset to 3 years which are from 2006 to 2008 due to how big the dataset his for the whole years.

### Data Wrangling process
> The 3 year dataset that was use for this analysis was read together using pandas as was combined together using append function.
> The column or variables header was changed so as to have a consistent as well as meaninful headers using rename function

## Summary of Findings

> - From the analysis we discover a huge variation from month to month, Days of week to Day of week on delays
> - However, we have a different variation from year to year on delay with no huge variation
> - Also, delay due to security is the least out of all other factor having the lowest variation
> - It was concluded that we had the highest delay of the week due to Weather delay on Tuesday and Friday while on Monday and Tuesday Late Aircraft Delay had it highest delay of the week.
> - Furthermore, AA( American Airlines) has the most Arrival delay.
> - finally, MQ(Envoy Air), AA(American Airlines) and OO(Sky West Airline) had the highest flight flight cancellation


## Key Insights for Presentation

> - Distribution of Carrier with highest Cancellation
> - Distribution of most common reason for flight cancellation.
> - Carrier productivity by flight Arrival Time
> - Trend of flight delay factors by Month to Month
> - Trend of flight delay factors by Year to Year

# NYC-flights
## Research Question: 
What factors are associated with departure delays for flights departing from New York City airports in 2013?
## Data source: 
This project uses the nycflights13 database from nycflights13 package in R. It covers flights leaving EWR, JFK and LGA in 2013. 
## Tools: 
SQL, SQLite, R, ggplot2
## Observations: 
This exploratory data analysis (EDA) provided multiple directions for further analysis. 
- What airport a flight departed from, whether EWR, JFK or LGA, was associated with different average arrival delays and indicates investigating factors causing delays by airport is a good next step.
- Departure delays appear to vary by month, with June and July having the highest average delays. The time of departure also appears to be a potential cause of delay, with flights departing around 8 having the highest average delays while flights leaving early in the morning had the lowest departure delays.
- No unadjusted weather phenomenon, from rain to visibility, appeared to have a strong association with departure delays. 
## Limitations:
This analysis has several limitations with the largest being no statistical tests have been carried out. Serving only as EDA for potential upcoming statistical analysis, none of the graphs or tables show causality or statistical significance. Another limitation is that delay data from all three airports is being analyzed together, Future analysis could analyze them separately or include origin airport as a predictor. Finally, flights with no recorded departure delay were excluded, which may have affected results. 
## Visualization

![Average departure delay by origin airport](output/figures/delay_by_origin.png)
![Average departure delay by Scheduled Hour](output/figures/delay_by_hour.png)

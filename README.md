# Surfs_up

## Overview of Analysis Strategy
Statistical analysis of temperature data for the months of June and December in Oahu, Hawaii, in order to determine if a surf and ice cream shop business is sustainable year-round.

### Software
Data was filtered using Python, Pandas functions and methods, and SQLAlchemy.

### Strategy
Independently retrieved all the temperature data for the months of June and December between the years of 2010 and 2017. The data extracted was converted to a list, then to a DataFrame and used to generate the summary statistics.

## Results
### June

[Temperature Statistics: June](june_temps_description.PNG)

![june_temps_description](https://github.com/coralrofa/surfs_up/blob/main/Resources/june_temps_description.PNG)

### December

[Temperature Statistics: December](dec_temps_description.PNG)


![dec_temps_description](https://github.com/coralrofa/surfs_up/blob/main/Resources/dec_temps_description.PNG)

### Conclusion
* There are about 200 measurements less for the month of December. 
* The average temperature for both months is close and based on the standard deviation, temperature is relatively constant with few spikes of high or low temperature.
* Max temperatures for both June and December are in the lower 8° F 0.
* Min temperatures show the most difference with 64° F for June and 56° F for December

## Summary
* The Temp profile for Oahu is constant throughout the year. 
* The two additional queries that would provide more information are (1) quarterly temperature statistics to increase resolution on temperature patterns and (2) the corresponding precipitation for those months since heavy rain can limit accessibility to the location. 

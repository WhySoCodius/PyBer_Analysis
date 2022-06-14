# PyBer_Analysis
-----
## Project Overview

The purpose is to perform an exploratory analysis to assist PyBer in improving ride-sharing services by providing a visual overview of PyBer's ride-sharing data by city type (Urban, Suburban, Rural) and comparing performance within cities. Demonstrate the relationship between city type, number of drivers, riders, and trip fares. 

Python modules such as Matplotlib and NumPy are used to plot DataFrames in order to complete this analysis.

## Resources

### Data Sources: 
Data files used for analysis are [Ride Data](/Resources/ride_data.csv) and [City Data](/Resources/city_data.csv)

### Software:
[![Anaconda-Server Badge](https://anaconda.org/conda-forge/terraform-provider-github/badges/version.svg)](https://anaconda.org/conda-forge/terraform-provider-github)
[![PyPI - Python](https://img.shields.io/pypi/pyversions/iconsdk?logo=pypi)](https://pypi.org/project/iconsdk)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

## Results

In this study, there are just three types of cities: urban, suburban, and rural. A brief overview of the findings can be seen in the DataFrame below.


![Ride_Data](/analysis/Ride_Data.png)


### Urban Cities
[With 68 percent of total trips](/analysis/Fig6.png) and [81 percent of total drivers](/analysis/Fig7.png), Urban City has the most drivers and rides of any city. This has a significant impact on average fare per ride and average fare per driver, with $24.53 and $16.57, respectively, being the lowest in our sample. Urban cities have 30 times the number of drivers as rural cities.

- Urban City has highest amount of earnings with $39,854.38
- Urban City has lowest Average Fare per Ride with $24.53, i.e low cost per ride for Riders.
- Urban City has lowest Average Fare per Driver with $16.57, i.e low earning per ride for Driver.

![Urban_Rides](/analysis/Fig1.png)

### Suburban Cities
Of all Suburban cities have low number drivers and rides, with 26% of the Total Rides and 16% of the total Drivers.
![image](https://user-images.githubusercontent.com/104621377/173481755-46266804-12cd-409f-976e-097006fb827d.png)

- Suburban City has average amount of earnings with $19,356.33
- Suburban City has Average Fare per Ride with $30.97, i.e $30.97 average cost per ride for Riders.
- Suburban City has Average Fare per Driver with $39.50, i.e $39.50 average earning per ride for Driver.


![Total_Rides](/analysis/Fig6.png)

### Rural Cities
Of all Rural cities have least number of drivers and rides, with both close to 5% of the Total and due to few drivers Rural City has the highest Average fare per Ride and Average fare per Driver at $34.62 & $55.49 respectively.

- Rural City has lowest amount of earnings with $4,327.93
- Rural City has highest Average Fare per Ride with $34.62, i.e more cost per ride for Riders.
- Rural City has highest Average Fare per Driver with $55.49, i.e more earning per ride for Driver.

![Ride_Fare_Data](/analysis/Fig3.png)





## Summary

![PyBer_fare_summary](/analysis/PyBer_fare_summary.png)

- Because there are more rides in the Urban City, the supply of Drivers increases, lowering the Urban City type's average.
- In the period Jan-Apr, Urban City's all-time high earnings are close to $2500, whilst Rural City's earnings are only $500. There is a significant gap in earnings that needs to be addressed by advertising and attracting customers to use Pyber services with promotions and offers.

![City_Data](/analysis/City_Data.png)
![Fare_City_Data](/analysis/Fig5.png)
- PyBer has to expand its reach in rural areas; PyBer has a 4 times lessor reach in Rural City then that of urban areas.
- The Average Ride Fare in the Rural City is the highest due to a scarcity of drivers. PyBer should effectively market its services to encourage drivers to pick up rides in rural areas.



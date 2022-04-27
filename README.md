# GV_Portfolio
data portfolio

# Project 1: Choropeth maps
## India population density
![](images/newplot_India%20PD.png)

## India Sex ratio scale
![](/images/newplot_India%20SRS.png)


# [Project 2: Local MSA Real Estate market](https://github.com/fyrtoes/2022-p2-housing)
* Extracted local real estate market data
* Interpolated missing time-series data to account for all span of time (1-day frequency)
* Missing data on the outer bounds was kept constant
* Calculated monthly payment from data provided
* Simplified visualization to a single axis by ploting time vs magnitude from original datapoint @ t=0
* Median home price, interest rate, and monthly payment are all relative values to initial datapoint

## Effect of Quantitative Easing/Tightening on local housing market
![](/images/SA_housing_Final.png)


# [Project 3: COVID data exploration with SQL queries](https://github.com/fyrtoes/2022-p3-SQL-Covid)
* Obtained data from: [Source](https://ourworldindata.org/coronavirus)
* Split raw data into two #.xlsx, then joined 
* Compared values between countries and continents
* Created new fields from calculations
* Created a temporary table
* Created View for further data consumption in visualization products

## Code and Resources Used
**SQL version:** Microsoft SQL Server 2019 - 15.0.2000.5  
**SQL Server MGMT Studio Version:** 15.0.18410.0


# PyBer_Analysis

    Analysis of all PyBer rideshare data from January to early May of 2019 with compelling visualizations.

## Overview of the Analysis

### Background

    Pyber would like to learn how its business is affected by the type of city that its drivers are operating within. This analysis will breakdown how the variations among fares across three city types can impact average fare per ride and driver respectively. By learning this, PyBer decision-makers will more accirately be able to adjust and adapt their business model for future growth.

## Results

### Differences Among City Types

    In reviewing the Pyber Summary dataframe below, note the significant value ranges across every metric for the three city types. Total Rides and Total Drivers generally follow expected trends based off the city type. In other words, you would expect fewer rides and fewer drivers in a rural city when compared to an urban city. However, the Average Fare per Ride and Average Fare per Driver results share a much more interesting story.

![Pyber_Summary_df.png](https://github.com/stovepipe/PyBer_Analysis/blob/main/Analysis/Pyber_Summary_df.png)

    In comparing the Average Fare per Ride versus Average Fare per Driver for Rural cities, notice that 'per Driver' is $20 more than 'per Ride', showing a significant positive return from their time driving. Suburban cities share a similar story, with drivers still showing a postivive return from their time driving, albeit a much smaller margin. Urban cities cross the threshhold and show a negative return from their time driving, making almost $8 dollars less than the Average Fare per Ride. 

    The weekly total fare by city type, as referenced in the graph below, shows that the total weekly fares rise and fall proportionately over time, regardless of the city type, demonstrating that the external variables of riders and fares will remain constant. This leaves room for Pyber decision-makers to adjust the business model to maximize the return for the driver's time.

![PyBer_fare_summary.png](https://github.com/stovepipe/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

## Summary

### Analysis identified three business recommendations to the CEO for addressing disparities among the city types.

    1. Recommended that PyBer explore ways to reduce the number of drivers in Urban cities. With so many drivers, PyBer has oversupplied the urban market, diminishing returns for drivers.
    2. Recommended that PyBer explore ways to increase the number of drivers in Rural cities. In its current state, Pyber has undersupplied the rural market so much so that the drivers who do operate in rural settings show significant returns for the driver's time.
    3. Final recommendation is to adjust operations across all three city types to reflect the ratio of rides to drivers as shown in the Suburban city type. The suburban Average Fare per Driver is still higher than the Average Fare per Ride, incentivizing drivers with positive returns, while efficiently meeting market demand for PyBer.
# PyBer_Analysis

*Prepared for V. Isualize on January 31 2021*

## Overview of Analysis

The purpose of this analysis is to create a summary DataFrame of the ride-sharing data from the beginning of January 01 2019 to the end of April 2019. A multiple-line graph showing the total weeky fares for each city type will also be delivered alongside the summary to show how the data differs by city type, thus helping decision-makers at PyBer.

## Results

The following DataFrame is a summary of the differences in ride-sharing data among **urban, suburban**, and **rural**:

![PyBer_Summary_DataFrame](/Analysis/PyBer_Summary_DataFrame.png)

As shown in the above summary DataFrame, the following points are observed:

* The **Urban** city type came in the highest for *Total Rides* at **1,625**, which is **2.6x** more than **Suburban** at **625**, and **13x** more than **Rural** at **125**
* The **Urban** city type also came in the highest for *Total Drivers* at **2,405**, which is roughly **4.9x** more than **Suburban** at **491**, and **30.8x** more than **Rural** at **78**
* The **Urban** city type had the highest *Total Fares* amount at **$39,854.38**, which is about **2.1x** more than **Suburban** at **$19,356.33**, and **9.2x** more than **Rural** at **$4,327.93**
* The **Rural** city type had the highest *Average Fare per Ride* at **$34.62**, which is roughly **1.1x** more than **Suburban** at **$30.97**, and **1.4x** more than **Urban** at **$24.53**
* The **Rural** city type had the highest *Average Fare per Driver* at **$55.49**, which is about **1.4x** more than **Suburban** at **$39.50**, and **3.3x** more than **Urban** at **$16.57**

* Overall, the **Urban** city type had the highest number of *Total Rides*, the highest number of *Total Drivers*, and the highest amount of *Total Fares*, and although the **Rural** city type had the lowest number of *Total Rides*, the lowest number of *Total Drivers*, and the lowest amount of *Total Fares*, it had the highest *Average Fare per Ride* as well as the highest *Average Fare per Driver*

The following graph is a multi-line chart depicting a summary of the *Total Fares* over the months of January to April in the year 2019:

![Pyber_Fare_Summary](/Analysis/PyBer_Fare_Summary.png)

As shown in the above summary multi-line chart, the following points are observed:

* The **Urban** city type maintained the highest total monthly fares, while the **Rural** city type held the lowest total monthly fares
* **Urban** and **Suburban** city types peaked around the end of February, while the **Rural** city type peaked as April started
* The **Suburban** city type is the only city type on an upward trend at the end of the 4 month period as April moved into May

## Summary

Based on the results, there are three business recommendations to address the disparities among the city types:

* Dispersing some of the urban drivers into the more rural areas may create more driver availability for customers, especially as there are roughly 30x the amount of drivers in the urban areas yet more than 3x the amount of average fares per driver in rural areas (this may reduce the average fare type but increasing the overall total fares from the rural areas)
* With only a fifth of the number of drivers, the suburban city type still brings in nearly half of the total fares as the urban city type does, so it would be wise to expand driver availability within the suburban city type, especially leading into the summer period
* The end of February shows a spike in all three city types, and it would be wise to ensure increased driver availability at this time, possibly with increased rates to optimize total fares for the month
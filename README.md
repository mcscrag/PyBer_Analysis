# PyBer_Analysis

## Analysis Overview

#### The goal of this analysis was to utilize the available data to create a dataframe for each city type in Pandas. Then to combine these dataframes to create a summary dataframe and multiple-line graph showing the total fares ride-share fares by city type. 

## Results

### Ride Share Data by City Type

![Summary Dataframe](/Resources/Summary_df.pmng)

#### The above dataframe gives summary data for each city type. The majority of PyBer's ride-share revenue comes from urban and suburban rides. However, each individual rural ride has almost 3 times the value of each urban ride. There could be many reasons for this, such as ride distance being generally longer in rural areas, or the urban areas have a saturation of drivers and thus the competition brings the average fare down. To further support this, the rural areas average 0.63 drivers per ride, whereas the urban areas average 1.5 drivers per ride. This data suggests it would be very cost effective to incentivize more rural drivers to bring the driver-to-ride ratio closer to 1 since each driver would create more value than urban drivers.

### Multiple-line Graph

![Multiple line Chart](/Resources/chart.png)

#### The above line chart plots the total fares for each city type over the first four months of 2019 in weekly intervals. It supports the above summary data in suggesting the majority of PyBer revenue is in urban and suburban rides. 

## Summary

### Recommendation One

#### Since the driver-to-ride ratio is only 0.63 in rural areas, and 1.5 in urban and the average fare-per-driver in rural areas is 3 times urban areas, this suggests there are some very cost effective dollars to be made by incentivizing rural drivers to bring the driver-to-ride ratio closer to 1. The same is true for suburban drivers to a lesser extent, showing a 0.79 driver-ride-ratio and double the average urban fare-per-driver.

### Recommendation Two

#### Increase the fees in urban areas. With 1625 rides compared to just 750 for both suburban and rural rides combined, this would be the most effective area to increase price as more people are dependent on the service in these areas.

### Recommendation Three

#### Target urban areas first for future expansion of the service. Total revenue from urban areas is much higher and thus cities are the most urgent areas to expand our ride-share service into.
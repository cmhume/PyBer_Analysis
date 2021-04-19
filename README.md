# PyBer Analysis


## Overview:


The purpose of this analysis is to document and provide recommendations for addressing disparities found in ridesharing data between three different city types: Urban, Suburban, and Rural. Data from the city_data.csv and ride_data.csv files were used as the basis for this analysis.  The city_data.csv file included information on the name of the city, the number of drivers in the city, and the city type (urban, suburban, or rural).  The ride_data.csv included information on the city name, the date, the fare, and the ride id.  The data included 120 different cities and a total of 2,375 rides during the year 2019.  These csv files were merged together in jupyter notebook on the city column to create the pyber_data_df dataframe.  Totla fares per week from each city type were later graphed over a four month period from January to April 2019. Pandas and matplotlib were used in the PythonData environment to create dataframes and graphs.

## Resources:


city_data.csv: https://github.com/cmhume/PyBer_Analysis/blob/dc0cf72a0efb8cc5f8f3c1124bdf269d1599f02b/Resources/city_data.csv


ride_data.csv: https://github.com/cmhume/PyBer_Analysis/blob/dc0cf72a0efb8cc5f8f3c1124bdf269d1599f02b/Resources/ride_data.csv


PythonData environment in Jupyter Notebook using:


Python 3.7


Matplotlib


Pandas


## Results:


![total_rides](https://user-images.githubusercontent.com/78699521/115163692-67dff580-a05f-11eb-8fc7-e5332bfbeef0.png)


### Total rides 

* Urban cities had the greatest number of total rides with a total count of 1625.  This was two and a half times the number of rides in suburban cities (625) and thirteen times the number of rides in rural cities (125).  


### Total drivers 


* Urban cities had the greatest number of drivers with a total count of 2405.  This was almost five times as many drivers as suburban cities (490) and close to thirty one times the number of drivers in rural cities (78). 

### Total fares


* Urban cities had the greatest total fares of all city types with a grandtotal of $39,854.38.  Suburban cities total fares were  $19,356.33.  Rural cities had the least total fares with a grandtotal of $4,327.93.

### Average fare per ride  


* Rural cities had the highest average fare per ride at $34.62.  Suburban cities had the second highest average fare per ride at $30.97.  Urban cities had the lowest average fare per ride at $24.53


### Average fare per driver 


* Rural cities had the highest average fare per driver at $55.49.  Suburban cities had the second highest average fare per driver at $39.50. Urban cities had the lowest average fare per driver at only $16.57.


### Total weekly fare by city type


![PyBer_fare_summary](https://user-images.githubusercontent.com/78699521/115163475-30247e00-a05e-11eb-9dc2-1381c292bf94.png)


* Total weekly fares followed the pattern of total fares with urban cities having the greatest weekly fares, suburban cities the second greatest total weekly fares, and rural cities the least total weekly fares.  The fourth week in February was a high point in weekly fares(tied with the second week in March for Urban cities) for all city types over the four month period from January to April of 2019.  The first week of January had the lowest total weekly fares for urban and suburban cities, while the second week in January had the lowest total weekly fares for rural cities.  


# Summary:

As can be seen from the data above, urban drivers receive the lowest average fare per driver among city types at only $16.57 compared with $55.49 average fare received for rural drivers.  This is inspite of the  closer range in average fare per ride, $24.53 for urban cities and $34.62 for rural.  Though the miles per ride were not used in this analysis, the total number of drivers per city type and total number of rides needed per city type may have an affect on the average fare per driver. Decreasing the number of urban drivers and increasing the number of suburban and rural drivers could increase the average fare per driver in urban cities makeing payments received more equitable amony drivers.  Currently, the number of urban drivers exceeds the number of rides given.  This  increases competition among drivers and likely results in cheaper fares when compared to other city types.  If urban drivers are reduced to a level closer to the total number of rides expected, average fare per driver will likely increase while total rides will stay in a similar range, increasing revenue overall.  Increasing the number of rural and suburban drivers to a level that is closer to the total number of rides may reduce the average fare per ride for consumers in those areas, making it more affordable. This may lead to an increase in rides in those city types and as long as the fare is not to low result in higher total fares overall.  Keeping track of miles per fare may also provide insight into disparities among fares received by drivers among city types.  The final reccommendation is to increase or decrease the number of drivers or the price per fare depending on consumer demand. The figure Pyber_fare_summary.png shows increased activity in the third week of February and decreased rides during the beginning of January.  Increasing fares during periods of high consumer demand when total rides are not likely to be affected can increase total revenue. 




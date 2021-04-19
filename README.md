# PyBer Analysis


## Overview:


The purpose of this analysis was to document and provide recommendations for addressing disparities found in ridesharing data between three different city types: Urban, Suburban, and Rural. Data from the city_data.csv and ride_data.csv files was used as the basis for this analysis.  The city_data.csv file included information on the name of the city, the number of drivers in the city, and the city type (urban, suburban, or rural).  The ride_data.csv included information on the city name, the date, the fare, and the ride id.  The data included 120 different cities and a total of 2,375 rides during the year 2019.  These csv files were merged together in jupyter notebook to create the pyber_data_df dataframe.  Total fares per week from each city type were later graphed over a four month period from January to April 2019. Anaconda's Jupyter Notebook, Pandas and Matplotlib were used in the PythonData environment for this analysis.


## Resources:


files:


city_data.csv: https://github.com/cmhume/PyBer_Analysis/blob/dc0cf72a0efb8cc5f8f3c1124bdf269d1599f02b/Resources/city_data.csv


ride_data.csv: https://github.com/cmhume/PyBer_Analysis/blob/dc0cf72a0efb8cc5f8f3c1124bdf269d1599f02b/Resources/ride_data.csv


PythonData environment in Jupyter Notebook using:


Python version 3.7.9


Anaconda version 2020.11


Pandas version 1.1.3


Jupyter version 1.0.0


## Results:


Results in Jupyter Notebook can be found here: https://github.com/cmhume/PyBer_Analysis/blob/497a31528340133106892178f63a788bf0e2d5f9/PyBer_Challenge.ipynb


PyBer Summary DataFrame:


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


#### Code used to create the PyBer summary dataframe:


![summary_code](https://user-images.githubusercontent.com/78699521/115172431-1db83d80-a07a-11eb-9190-8782bd1fca83.png)


### Total weekly fare by city type


* Total weekly fares followed the pattern of total fares with urban cities having the greatest weekly fares, suburban cities the second greatest total weekly fares, and rural cities the least total weekly fares.  The fourth week in February was a high point in weekly fares(tied with the second week in March for Urban cities) for all city types over the four month period from January to April of 2019.  The first week of January had the lowest total weekly fares for urban and suburban cities, while the second week in January had the lowest total weekly fares for rural cities.  Figure available at: https://github.com/cmhume/PyBer_Analysis/blob/e3ded26b18912ba7f0ab3a6e65404e39e3e6758d/analysis/PyBer_fare_summary.png


#### Code used to create  PyBer Fare Summary:



![PyBer_fare_summary](https://user-images.githubusercontent.com/78699521/115163475-30247e00-a05e-11eb-9dc2-1381c292bf94.png)


![fares_by_week_2](https://user-images.githubusercontent.com/78699521/115172571-640d9c80-a07a-11eb-954a-16ff215f7680.png)


# Summary:

As can be seen from the data above, urban drivers received the lowest average fare per driver among city types at only $16.57 compared with the $55.49 average fare received for rural drivers.  Though the miles per ride were not used in this analysis, the total number of drivers per city type and total number of rides needed per city type may have an affect on the average fare per driver. Decreasing the number of urban drivers and increasing the number of suburban and rural drivers could increase the average fare per driver in urban cities increasing equity in the fares received by drivers in different city types.  Currently, the number of urban drivers exceeds the number of rides given.  This  increases competition among drivers and likely results in cheaper fares when compared to other city types.  If urban drivers are reduced to a level closer to the total number of rides expected, average fare per driver will likely increase while total rides will stay in a similar range, increasing revenue overall.  Increasing the number of rural and suburban drivers to a level that is closer to the total number of rides may reduce the average fare per ride for consumers in those areas, making it more affordable. This may lead to an increase in rides in those city types and result in higher total fares overall.  Keeping track of miles per fare may also provide insight into disparities among fares received by drivers among city types.  In addition,  increasing or decreasing the number of drivers or the price per fare depending on consumer demand can help keep the fare per driver at a similar rate in each city type while increasing total revenue. The figure Pyber_fare_summary.png shows increased activity in the third week of February and decreased rides during the beginning of January.  Increasing fares during periods of high consumer demand when total rides are not likely to be affected can also increase fare per driver in urban cities. 




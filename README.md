# PyBer_Analysis
Creating visualizations of rideshare data for PyBer to help improve access to ride-sharing services and determine affordability for underserved neighbourhoods.

## Overview of Project

This project regarding Module 5: PyBer, is a ride-sharing application organization. We will play out an exploratory investigation of data in a large csv records to make an assortment of graphs that feature the connection between the sort of city, and the quantity of drivers and riders, just as as the percentage of the total fares, riders and drivers by type of city. The results and findings will assist the PyBer with further improve access to ride-sharing services and determine affordability for underserved neighbourhoods

As Data Analyst, we are working with Jupyter Notebook and Pandas, using Python's Library such as Matplotlib, SciPy, NumPy. We work with crude information data from CSV reports, inspect data, Merge data sets, Perform Calculations, create data series, data frames, and data visualization. Likewise, we utilized Matplotilb to make graphs, for example, line charts, bar charts, scatter plots, bubble charts, pie charts, and box-and-whisker plots showing discoveries in a valuable and connecting way to all stakeholders. Also, we utilized Pandas, SciPy and NumPy to perform summary statistics. This assignment is related to the Bootcamp Data Analytics from the University of Toronto.

For data analysis, three files were used; [PyBer_ride_data.csv](https://github.com/DougUOT/PyBer_Analysis/blob/main/Resources/PyBer_ride_data.csv), [city_data.csv](https://github.com/DougUOT/PyBer_Analysis/blob/main/Resources/city_data.csv) and [ride_data.csv](https://github.com/DougUOT/PyBer_Analysis/blob/main/Resources/ride_data.csv),representing 2,375 rides in 121 cities with information such as average fare in US$ per month, provided by the company PyBer.

Follow below the goals for this module:

1) Using pictures from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
2) Based on the outcomes, give three business suggestions to the CEO for addressing any disparities among the city types

## Resources

* Data Source: [PyBer_Challenge.ipynb](https://github.com/DougUOT/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)
* Software: Python 3.8.8, Anaconda 4.11.0, Jupyter Notebook 6.4.6, Pandas 1.3.4, Matplotlib 3.4.3, Numpy 1.20.3 and SciPy 1.7.1

## Results

### Objective 1

  * The total number of rides for each city type is retrieved.
  * The total number of drivers for each city type is retrieved.
  * The sum of the fares for each city type is retrieved.
  * The average fare per ride for each city type is calculated.
  * The average fare per driver for each city type is calculated.
  * A PyBer summary DataFrame is created.
  * The PyBer summary DataFrame is formatted as shown in the example.



### The total number of rides for each city type is retrieved

![](https://github.com/DougUOT/PyBer_Analysis/blob/main/Resources/Images/Results_Obj1.PNG)

Regarding the total of rides for each city type, we have  2,375 rides, 68% refer to urban rides, 26% to suburban, and just 5% is related to rural rides.  Urban and suburban rides represent 95% of the total rides for this company.

### The total number of drivers for each city type is retrieved

![](https://github.com/DougUOT/PyBer_Analysis/blob/main/Resources/Images/Results_Obj2.PNG)

About the total of drivers rides for each city type, we have  2973 drivers, 81% refer to urban drivers, 16% to suburban drivers, and just 3% is related to rural drivers.  Urban and suburban drivers represent 97% of the total rides for this company.

### The sum of the fares for each city type is retrieved.

![](https://github.com/DougUOT/PyBer_Analysis/blob/main/Resources/Images/Results_Obj3.PNG)

Regarding the sum of the fares for each city type, we have a total of $ 63k, with 63% referring to urban fares, 30% to suburban fares, and 7% related to rural fares.  Urban and suburban fares represent 93% of the total fares for this company.

### The average fare per ride for each city type is calculated

![](https://github.com/DougUOT/PyBer_Analysis/blob/main/Resources/Images/Results_Obj4.PNG)

As to the average fare per ride for each city type, the average fare per ride for rural is $34.62, followed by suburban with 30.97 and urban with $24.52.  We do have Rural and suburban with the highest average fare per ride.

### The average fare per driver for each city type is calculated

![](https://github.com/DougUOT/PyBer_Analysis/blob/main/Resources/Images/Results_Obj5.PNG)

Concerning the average fare per driver for each city type, the average fare per drive for rural is $55.48, followed by suburban with $39.50 and urban with just $16.57.  We do have Rural with the highest average fare per driver. Even for Suburban, the average fare per driver is more than double the average fare per driver for urban-type cities.

### The PyBer summary DataFrame

![](https://github.com/DougUOT/PyBer_Analysis/blob/main/Resources/Images/Results_Obj6.PNG)

We created the PyBer summary DataFrame with total rides, total drivers, total fares, average fare per ride and average fare per driver.

### The PyBer summary DataFrame formatted 

![](https://github.com/DougUOT/PyBer_Analysis/blob/main/Resources/Images/Results_Obj7.PNG)

The PyBer Summary DataFrame is arranged as displayed in the model above, adding the two-digit currency format for total fares, average fare per ride and average fare per driver

### Objective 2

### First business suggestion

After completing the data analysis in the files provided by the company and based on the results obtained, the first business suggestion would be to suggest the company balance the numbers of drivers per city type. The graphs below show that the number of drivers vs. ride per city type is unbalanced. For Urban rides, we have 1625 rides for 2405 drivers; this represents about 48% more drivers for each ride. On the other hand, we have more rides than rural and suburban drivers.

A practical suggestion would be to hire an additional 47 drivers to cover rural areas and 135 drivers for suburban areas, leaving at least one driver for each ride. With this suggestion, the company would have 125 drivers covering the same number of rural rides and 625 drivers for suburban areas covering the same number of suburban rides too.


![](https://github.com/DougUOT/PyBer_Analysis/blob/main/Resources/Images/Percentual_Rides_by_CityType_Fig6.PNG) ![](https://github.com/DougUOT/PyBer_Analysis/blob/main/Resources/Images/Percentual_Drivers_by_CityType.PNG)

### Second business suggestion

The second business suggestion would be to work on the pricing strategy and create a campaign focused on the rural area. This strategy would be in line with the company's objective to further develop admission to ride-sharing services and determine accessibility to underserved neighbourhoods or neighbourhoods with business opportunities. 

Based on the results and analysis, only 5% of rides take place in rural areas, and the value is the highest compared to other areas such as suburban and urban. Also, the marketing and sales department could evaluate the same idea to implement this same strategy for suburban areas to increase the number of fares for these city types.

In the graph below, the disparity among the rides by city types is evident, with the highest concentration for urban areas and the excellent opportunity to improve the ride-sharing for rural and suburban areas.

![](https://github.com/DougUOT/PyBer_Analysis/blob/main/Resources/Images/Results_PyBer_Fares_vs_Rides.PNG)


### Third business suggestion

Implementing the two business suggestions shared above, the company will create marketing campaigns for a few months or specific periods for each City type to increase the number of rides. 

Urban Area: The line graph below shows the results with total fares by City Type per month, there is a growing trend for urban fares, in January the total fares were just over $1500 and in April this The result was already above $2000, this region can be considered a stronghold for this company, as 68% of rides and 63% of the number of fares are concentrated in the Urban area. As a suggestion, the company could concentrate marketing investments for January and March. 

Rural area: As a suggestion, the company could create a marketing campaign with promotional prices for the first half of January to March. 

Suburban area: The suggestion would be to create marketing campaigns for the first half of February and March. 

Last but not least, according to the chart below, all city types (Urban, Suburban and rural) had an addition of rides in the second half of February so that the company could evaluate a marketing campaign or promotions in the first two weeks of February for all City Type.


![](https://github.com/DougUOT/PyBer_Analysis/blob/main/Resources/Images/Total_fare_by_citytype_by_Month.PNG)

## Summary

Abstract: With the three shared business suggestions above, the company will be able to improve access to ride-sharing services, determine accessibility to underserved neighbourhoods, and further develop admission to ride-sharing services.

For the future, it is recommended that the company perform a new data analysis compared with the latest results. After implementing the business suggestions, the company would change or create new marketing strategies or revise fare prices according to each City Type (Urban, Suburban or Rural) that meet the needs of stakeholders.



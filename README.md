![Challenge_fare_summary](https://user-images.githubusercontent.com/86276329/132288645-54b14209-497a-4f12-aba5-641cabe0eb85.png)
![city_data.csv](https://github.com/VCW2021/PyBer_Challenge.ipynb/files/7119056/city_data.csv)
![ride_data.csv](https://github.com/VCW2021/PyBer_Challenge.ipynb/files/7119058/ride_data.csv)
![README.md](https://github.com/VCW2021/PyBer_Challenge.ipynb/files/7119090/README.md)

The purpose of our Analysis is to create a summary DataFrameand to ride sharing data by showing the total number of rides for each city. The number of drivers for each city. The sum of the fares for each city and function used to provide the data to calculate the average fare per ride for each city and the average fare per driver for each city. We first pulled data using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time. When data was pulled and everything came together a DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare". In the second part DataFrame was created again using the loc method on the date range: 2019-01-01 through 2019-04-28. A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week. 

Results:

Rural cities has the lowest in ride-sharing data among the different city types. Urban cities has the most ride-sharing data include the total rides, Suburban meet in the middle with total drivers, total fares, ride and fares had the highest average fare per ride and driver in the Suburban, and Urban cites with the lowest average of fare ride and fare per driver.  

Summary:

We are able to compare and contrast our data based on what city type the customers take rides in. Even though we only explored few cites we still get an understanding on what fares will look like week by week. Finally, there's many more data we can analysis using different ways of how the date changes on a day to day basis. 


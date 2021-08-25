# surfs_up
Weather analysis project using SQLite and SQLAlchemy
## Overview:
### Gather temperature data for the months of June and December in Oahu, Hawaii, to determine if the surf-and-ice-cream shop business is sustainable year-round. 

## Results:
June Temperatures | December Temperatures
:------------------------------------------: | :------------------------------------------:
![June_temps](https://user-images.githubusercontent.com/74624855/130848080-9f35924e-355b-4abb-a00a-5c0d6b42fe25.png) | ![December_temps](https://user-images.githubusercontent.com/74624855/130848095-64f55223-32aa-4296-bf52-7899eab4f460.png)

1)	Temperatures in June and in December were comparably stable. 
    - The mean temperature for June was 74.94℉ with a standard deviation of 3.26.
    - The mean temperature for December was 71.04℉ with a standard deviation of 3.75.
    
2)	Based on the minimum temperatures for June and December, it can be concluded that December is generally somewhat cooler than in June, and this may result in a reduced           number of customers in December.
    - The minimum temperature for December was 56℉, compared with 64℉ in June. 
    
3)	The data count was higher for June, because there was data gathered for June 2017 but not for December 2017. This means that the weather stations gathered an extra set of       data that was not retrievable for December. Since the standard deviation was pretty close for both months, it’s unlikely the extra dataset for June has much of an impact on     the comparison for the two months.

## Summary:
### Using the summary statistics for June and December weather data, it appears that the surf-and-ice-cream shop can remain open year-round. The temperatures are warm enough for surfing and for customers buying ice cream, so the business should be reliable and profitable. 

Further, the following two queries could be run to provide even more accurate analysis of weather trends for June and December in Oahu for the business:

1)	Query for Precipitation trends in June and December. 
    - It’s reasonable to assume that people are less likely to go surf or for ice cream in the rain. We can run summary statistics for precipitation data in June and December         to see if there are reliable trends with regards to precipitation.
    
2)	Query temperature and precipitation results filtered by month and year, to determine if there are any years that are outliers.



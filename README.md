# PyBer_Analysis

## Overview of the analysis

### Background

V. Isualize and Omar have provided our team with 2 csv files containing ride share data and tasked our team to utilize Python and our knowledge of Pandas to create a summary DataFrame of the ride-sharing data by city type. We'll first use Pandas to create a summary DataFrame of the data by city type. To achieve this we need to clean the data sets(csv files), merge the files into one DataFrame based on city type, then calculate key metrics like driver count by type, ride count by type and total fares by type. Last we'll create a multiple-line graph that shows the total weekly fares for each city type to visualize the data.

### Resources:
- Python
- Pandas library
- Jupyter Notebook
- Matplotlib library

## Results:

The results can be visualized below:

Total fares are highest in Urban cities followed by Suburban cities with Rural cities pulling in the lowest total fares.

![PyBer_fare_summary](https://user-images.githubusercontent.com/107006216/180885286-bc767178-17dc-455e-97e7-b4d117887a9c.png)

Let break this down, based on the chart above one could be led to believe that Urban drivers recieve the hightest fare and Suburban and Rurual drivers recieve a lower fares respectively but this would be __wrong__. 
The reality is Urban cities have the highest volume of rides(higher demand) and the largest number of drivers, and in fact the average fares in an Urban city are much lower then other types. Urban cities average $24.53 per ride where as Suburban and Rural average $30.97 and $34.62 respectively. Its the large number of drivers and rides in Urban cities thats driving the higher total fare revenue.

The bubble chart below breaks down the average fare relative to the number of total rides and city type is a helpful way to visually explain the previous chart and the reason Urban total fares are the highest and total rural fares are the lowest.

![image](https://user-images.githubusercontent.com/107006216/180885880-ce1c0964-6d7c-4b9c-83c2-aba411bc1bdc.png)


## Summary and Recommendations:

![image](https://user-images.githubusercontent.com/107006216/181061249-d37637c0-a3bd-4054-932e-2d0288b058a8.png)

### Total Rides:
- Urban cities had the highest total number of rides at 1,625, significantly higher than Suburban cities at 625 and Rural citites,the lowest, at 125.

### Total Drivers:
- Urban Cities has the most with 2405 total drivers follwed by suburban cities at 490 and Rural Cities at 78. The differences between cities are even more significant here with Urban citiy drivers far exceeding those in suburban and rural areas.  This also helps explain the lower average fare and the significantly higher total fares for urban drivers. 

### Average Fare per Ride:
- The average Fare per ride has the exact opposite realtionship with city type that we saw with total rides and total drivers.  Rural cities had the highest average fare at $34.62 follwed by suburban cities at $30.97 and Rural cities at $24.53. This makes sense based on the data we've explored so far.  Fewer rides(less demand) all else being equal should drive the fare price down however because there are so few drivers in the Rural communities the price is actually higher. The number of drivers(supply) in this case outweighs the lower number of rides(demand) and increases the fares drivers in the Rural communities recieve.

### Total Fare/Tota Fare by City:
- The total urban fare is the highest depsite Urban drivers making on average the lowest fare. The higher number of rides and drivers are driving the total Urban to exceed that of other city types.

### Recommendations
- Our analysis has given us an idea of demand in different city types and we know the supply of drivers(driver count) as well as the fare they are earning.  Given what we know my first recommendation is to determine the optimal ratio of drivers and the fare to charge based on a fluctuating demand for rides. The fare can we increased or decreased which it tern will impact the demand for rides and the supply of drivers.  When the fare is to low the demand for rides may surge however there wont be enough drivers to take those rides at that price. Finding the optimal fare base on ride and driver estimates will enable this ride-sharing company to maximize profit in real time. It may be in the interest of the company to increase the fare for Urban drivers although without more informtaion its hard to make that recommendation as i do not know what impact that would have on demand.

- I would also recommend investing in an additional study to investigate the fluctutations in the total fares by city during the year. We can see there are spikes toward the end of February across all city types. Understanding what is driving the increased total fares during those times could give us important insight on how to drive up revenue at other times during the year. Is it related to the number of drivers on the road, the fare, or the number of rides(demand) taken.  Drilling into this would give us valuable insight.

- Additionally investing in an even more granular analysis that broke up Urban data by neighborhood would allow us to target in demand areas or add drivers to areas that have previously been overlooked.





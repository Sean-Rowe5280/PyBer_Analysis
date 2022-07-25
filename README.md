# PyBer_Analysis

## Overview of the analysis

### Background

V. Isualize and Omar have provided our team with 2 csv files containing ride share data and tasked our team to utilize Python and our knowledge of Pandas to create a summary DataFrame of the ride-sharing data by city type. We'll first use Pandas to create a summary DataFrame of the data by city type. To achieve this we need to clean the data sets(csv files), merge the files into one DataFrame based on city type, then calculate key metrics like driver count by type, ride count by type and total fares by type. Last we'll create a multiple-line graph that shows the total weekly fares for each city type to visualize the data.

### Resources:
- Python
- Pandas library
- Jupyter Notebook
- Matplotlib library
-
## Results:

The results can be visualized below:

Total fares are highest in Urban cities followed by Suburban cities with Rural cities pulling in the lowest total fares.

![PyBer_fare_summary](https://user-images.githubusercontent.com/107006216/180885286-bc767178-17dc-455e-97e7-b4d117887a9c.png)


Let break this down, based on the chart above one could be led to believe that Urban drivers recieve the hightest fare and Suburban and Rurual drivers recieve a lower fares respectively but this would be __wrong__. 
The reality is Urban cities have the highest volume of rides(higher demand) and the largest number of drivers, and in fact the average fares in an Urban city are much lower then other types. Urban cities average $24.53 per ride where as Suburban and Rural average $30.97 and $34.62 respectively. Its the large number of drivers and rides in Urban cities thats driving the higher total fare revenue.


Urban:

![image](https://user-images.githubusercontent.com/107006216/180887436-8fafeb07-5093-4743-a00e-5c0cd9ae3e40.png)

Suburban:

![image](https://user-images.githubusercontent.com/107006216/180887456-03bac704-29c8-4e3f-966e-e43ca72d015b.png)

Rural:

![image](https://user-images.githubusercontent.com/107006216/180887484-c5a38538-8126-4185-b040-ab4d71ee3137.png)

The bubble chart can help us visualize this:

![image](https://user-images.githubusercontent.com/107006216/180885880-ce1c0964-6d7c-4b9c-83c2-aba411bc1bdc.png)








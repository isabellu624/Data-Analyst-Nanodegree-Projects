# Project 1 - Exploring Weather Trends

## Step 1: Extract Data
```
#Extract the csv and saved as LAcity_data#
Select * from city_data where city=’Los Angeles’ and country=’United States’
#Extract the global_data and save the csv#
Select * from global_data
```
## Step 2: Generate Line Chart
The two data set were combined into one excel file and only the data of the same years were kept.
10-years moving averages were calculated for LA_data and global_data respectively.
A scatter chart was generated and titles were edited.
Correlation coefficient between these two sets of data is calculated by using CORREL(array1,array2)
Trend lines and R2 values are shown in the chart for the following discussion and interpretation.
 
 
## Step 3: Data Interpretation
### Observation 1: 
LA is hotter on average compared to the global average, due to its subtropical location. The difference has been consistent over time. 
### Observation 2:
According to the chart, LA temperature is more fluctuant than the global temperature, with more variations along the time. The trend of LA temperature is not consistent. It goes up and down during the first 100 years, but turns consistently up after 1970. Verified by the relatively low R2 value of 0.3778.
### Observation 3:
The global temperature is more flattened and consistent going up over time, with a high R2 value of 0.8557.
### Observation 4:
In general, LA temperature trend and global temperature trend are consistent with a high correlation coefficient of 0.76. The trend lines of these set of data shows that both LA and the world is getting hotter. 



## Bike Data Project by Rosalie El Ouardi

### Introduction

>Ford Go Bikes and Bay Wheels, bike sharing programs through Lyft, have provided us data regarding their trips with the following information: trip duration in seconds, start date and time, end date and time, start and end station IDs, start and end station names, start and end station latitudes, start and end station longitudes, bike id, and user type (where casual means customer and member means subscriber.)

### Assessing Data
>Here, I just looked at the data with a few different functions to see what was presented to me and how I could add to it.

### Cleaning Data
>In this section, I added several new columns regarding dates and time to be able to further analyze the data.

### Univariate Exploration of Data
>Question 1: What are the most common starting and ending station locations?
>>I answered this question with two horizontal bar charts.
>
>Question 2: What is the user type distribution?
>>This question was answered with a pie chart.
>
>Question 3: Which days are most popular for bike usage?
>>This next question was answered with horizontal bar chart. 
>
>Question 4: What is the length of the average ride?
>>This last question in the univariate section was answered with a histogram.

### Bivariate Exploration of Data
>Question 5: What is the correlation between day of the week and trip duration?
>>I tried to answer this question with a regplot but ended up answering it with a violin plot.
>
>Question 6: Which days are the most popular for bike usage by user type?
>>I answered this question with two vertical bar charts.
>
>Question 7: What is the rental time distribution by user type?
>>This question was answered with a box plot.
>
>Question 8: Where are the starting station locations on a map?
>>This last question in the bivariate section was answered using geopandas and three .json maps.
>

### Multivariate Exploration of Data
>Question 9: What is the average trip duration per user type per month?
>> This question was answered with a strip plot. 
>
>Question 10: What hours are most popular for bike usage?
>>I attempted to answer this last question with a strip plot, but found a heatmap was more appropriate.
>
### Findings

 - The top starting and top ending stations were mostly the same and located in the San Francisco area. The stations in general were clustered in three areas in the Bay area. The starting stations were in the northeast corner of San Francisco and the top 5 starting stations were in the far northeast of San Francisco. 
 - Subscribers were nearly 80% of the user type for this service in 2017.
 - Tuesdays and Wednesdays were more popular usage days than Saturday or Sunday in general but, when analyzed based on user type, the weekends were much more popular with customers and the weekdays were more popular with subscribers. The large amount of subscribers skewed the data. 
 - The average trip is nearly 10 minutes and majority of trips are under 30 minutes and trips were in longer duration during the weekends. It also showed these longer trips on the weekends were ones taken by customers and not subscribers. 
 - The hours that are most common during the weekdays for bike usage are when work usually starts (7 am to 10 am) and when it ends (5 to 7 pm). On the weekends the usage seems to be more in the midday from 11 am to 5 pm. 

 

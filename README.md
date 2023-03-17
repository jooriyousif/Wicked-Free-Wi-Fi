# Wicked Free Wi-Fi: Analyzing Boston's Free Wireless Network
Wicked Free Wi-Fi is a program that provides free wireless internet access to residents and visitors in certain cities and towns in Massachusetts, United States. This project analyzes two datasets - [WICKED FREE WI-FI DAILY CONNECTIONS](https://data.boston.gov/dataset/wicked-free-wi-fi-daily-connections) and [WICKED FREE WIFI LOCATIONS](https://data.boston.gov/dataset/wicked-free-wifi-locations). The first dataset is used to identify trends and patterns in the number of daily connections to Wicked Free Wifi using Python's pandas library. The second dataset is used to create an interactive dashboard in Tableau to make it easier for people to find Wi-Fi hotspots in their area.

## Analysis In Python: 
This project is a data analysis of daily connections to the Wicked Free Wi-Fi network in Boston, Massachusetts from 2014 to 2016. The goal is to explore the data, clean and preprocess it, and perform exploratory data analysis to gain insights into the dataset. 

### Libraries Used:
pandas, numpy, matplotlib, plotly, chart_studio

### Data Cleaning and Preprocessing:
First I imported the dataset using pandas and stored it in a dataframe named df. Then I checked the data types of each column, the number of missing values, and the number of duplicated rows. I found that there were no missing or duplicated values, and I converted the date column to a datetime format using the pd.to_datetime() function. I also grouped the data by date using the groupby() to get a better understanding of the trends in connection data over time. 

### Conclusion:

![Daily Connections over Time](https://github.com/jooriyousif/-Wicked-Free-Wi-Fi/blob/main/line%20chart.png?raw=true)

The line chart shows the trend of daily connections over time for the free Wi-Fi program in Boston. The graph indicates that the program experienced significant growth from around 500 daily connections in September 2014 to over 8700 in mid-July 2015. However, there was a gradual decline in daily connections thereafter, suggesting that the program might have reached its saturation point. The dips in daily connections on certain dates could be due to external or internal factors. The line chart provides valuable insights for stakeholders to make data-driven decisions on how to improve the program.

![Total Connections by Neighborhood](https://github.com/jooriyousif/-Wicked-Free-Wi-Fi/blob/main/bar%20graph.png?raw=true)

The bar chart displays the total number of connections made in each neighborhood in Boston. Roxbury has the highest number of connections at over 1.1 million, followed by Downtown Boston and Parks with over 500,000 and 400,000 connections, respectively. Other neighborhoods such as Dorchester, Hyde Park, and Roslindale also have high numbers of connections. On the other hand, City Hall Truck and Columbus Park have relatively low numbers of connections. These insights can help stakeholders understand the areas with high demand for Wi-Fi and allocate resources accordingly.

![Connections by Neighborhood and Date](https://github.com/jooriyousif/-Wicked-Free-Wi-Fi/blob/main/heat%20map.png?raw=true)

The heatmap shows that Downtown consistently has the highest number of connections across all dates, and that there are higher concentrations of connections in certain neighborhoods on certain days. This suggests that the demand for free public Wi-Fi may be driven by factors such as events or weather conditions that affect specific neighborhoods more than others. The insights from the heatmap can help stakeholders plan for events and allocate resources to meet the demand for Wi-Fi in specific neighborhoods on certain days.


## Dashboard In Tableau: 
To make it easier for people to find Wi-Fi hotspots in their area, we've created an interactive dashboard using Tableau.
You can find the Dashboard here: 



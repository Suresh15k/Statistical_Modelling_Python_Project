# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of statistical modelling project using python is to pull data from different source using GET API and convert the available content to a suitable format for EDA . By using panda the data has to be cleaned and visualized using ploty , seaborn or any other relevant libraries. Try to find relations and derive valuable business insights. Finally do a linear regression analysis to validate the insights    

## Process
Connect to the CityBikes API and understand the data structure.
Choose a city covered by the CityBikes API and retrieve all available bike stations in that city.
Query the API for latitude, longitude, and number of bikes for each bike station.
Connect to the Foursquare API and Yelp API.
For each bike station, query both APIs to retrieve information on restaurants, bars, and other points of interest in that location.
Create separate dataframes for the Yelp and Foursquare results.
Compare the quality and coverage of the Yelp and Foursquare APIs based on your own criteria.
Join the data from the CityBikes API with the data from Foursquare and Yelp APIs to create a new dataframe.
Build a regression model using the statsmodels module to explore the relationship between the number of bikes and the characteristics of the points of interest. Interpret the results and derive insights from the model.

## Results
I am able to sucessfuly query multiple API and Parse through the response to get the Point og intrest details. I was able to combine all 3 different source of data and did exploratory data analysis and derive valuble insits and relations. finally created a linear regression modle for bikes avilable and the slots count. 

## Challenges 
Due to the limited data availability, it was challenging to establish a strong relationship between the restaurants and bike stations. With only 20 available restaurants compared to 700 bike stations in the city, conducting a meaningful comparison became difficult. Furthermore, most of the variables lacked a significant correlation making it dificult to find insights.

## Future Goals
Given more time, I would think about utilizing string and catagorical variable to find relation and insights. I would have done more practice with coding to improve my skills.

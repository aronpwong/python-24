# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of this project is to showcase my capabilities in python. The project 
first uses the CityBikes API with a chosen location (Denver, CO) to highlight the available bikes based on longitude and latitude. Afterwards, we will use Foursquare API and Yelp API to retrieve number of restaurants from each bike station in Denver. Once we retrieve the data, we will compare both data to determine the ease of accessibility and amount of data available. You will visualize the data by joining the data. In the end, you conduct regression model and determine which data provided good data based on the threshold.

## Process
Part 1 - CityBikes API
Choose a city and query bike stations from CityBikes API
Determine the latitude, longitude and bikes available
Parson JSON into Panda dataframe

Part 2 - Foursquare and Yelp
Connect Foursquare API and Yelp API
Using the bike station data from Part 1, query with each API
Create a dataframe for Foursquare results and Yelp results
Compare the data from both Foursquare results and Yelp results

Part 3 - Joing Data
Join the data from Part 1 and Part 2 into a new dataframe
Use data visualization to showcase the data
Create a SQLLite database and store data

Part 4 - Building Model
Build a regression model
Interpret results

## Results
(fill in what you found about the comparative quality of API coverage in your chosen area and the results of your model.)

## Challenges 
Foursquare and Yelp are hard to yield results due to limitation. Once you reach the usage limit, it creates a domino effect of data returned to tables. In addition, the way you organize the parameters will affect whether or not data can be pulled from Foursquare and Yelp. I was unable to pull data properly from Yelp without reaching my usage limit which greatly affected my data visualization and regression models. 

Depending on the density of the city, more data to process and filter.

Figuring out how to debug my codes so they can run. I had to get a lot of mentor help due to my limit exposure to Foursquare and Yelp API.



## Future Goals
Running more tests to ensure I'm yielding expected results and to debug codes. Asking for help more because mentors have more experience and provide great insights instead of me sitting there frustrated.

Reading instructions thoroughly so I don't end up doing the opposite of what I was asked to.

Develop a style guide for consistency. 

Documenting my process to understand the to do's and not to do's for future projects. This includes saving previous versions in case the current file is broken or unsalvageable.

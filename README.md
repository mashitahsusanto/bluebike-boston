# Boston Bike Share

Massachusetts, is one of the most bike-friendly states in the country, with Boston and Cambridge considered the best places for cyclists. With a population of 4.87 million, Boston is ranked No. 6 most bikeable city in the US. Since the late 19th century, cycling has been a popular activity in Boston, for both recreation and commuting around campuses of the numerous universities in the city. The state worked hard by investing in updated infrastructure, building roads with bicycle tracts, and founding one of the nation’s first public bike-sharing systems, Bluebike. 
  
BlueBikes is a government-owned bike-share company, all across Arlington, Boston, Brookline, Cambridge, Chelsea, Everett, Newton, Revere, Salem, Somerville, or Watertown. A user can pick up a bike at any station dock, ride it for a specific amount of time, and then return it to any station for re-docking.


# CONTENT 
- Hypothesis
- Goal
- Data
- The metrics for Model Selection
- Findings / Conclusion
- Limitations
- Future Work


# Hypothesis

How well can we predict a user's Trip Duration?


# Goal

To accurately point out what affects the duration of people using the Bluebike Bike share, i.e. the distance itself, the month of usage, day, time of day, gender, or even birth year.

The project also aims to establish a relationship between the duration and mileage of the bike.

The mileage is predicted using the Geopy method, where the latitude and longitude of its starting and ending position is calculated.
In order to fulfil the goal, this project contains both models done by linear and logistic classification. The classification model of choice is the standard logistic regression, KNN neighbour, and gridsearch, in order to identify the coefficient model, for predicting the features.


# Data

The data is downloaded from https://www.kaggle.com/jackdaoud/bluebikes-in-boston, which contains two dataset: "bluebikes_tripdata_2019.csv" "bluebikes_tripdata_2020.csv"
There are 2,522,771 rows and 17 columns for the first dataset (2019), and 1,999,446 rows & 18 columns for the second one (2020).
With the two dataset, it enables us to compare the difference in the trip duration of both years.





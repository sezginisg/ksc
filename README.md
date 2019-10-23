# ksc_project
In this notebook we will be working on the data set on houses from King's county. The aim of the notebook is to build a linear regression model which can help us predict sales price of houses in King's county. During the process we hope to find interesting relationship between different variables and select features that are most useful in prediction.
In order to begin analysis, the first thing we need to do is to set up our system by importing the appropriate libraries and the dataset we will be using.
In order to build our model we need to first understand our dataset and the variables that compose them. This dataset has 21597 observation and 21 columns. Out of these the ID has no predictive utility, apart from letting us know that it is the same property that is being sold again, and so we have 19 variables to work with. The data dictionary provides the following information about them
dateDate - house was sold
price - Price is prediction target
bedrooms - Number of Bedrooms/House
bathrooms - Number of bathrooms/bedrooms
sqft_living - square-footage of the home
sqft_lots - square-footage of the lot
floorsTotal - floors (levels) in house
waterfront - House which has a view to a waterfront
view - Has been viewed
condition - How good the condition is ( Overall )
grade - overall grade given to the housing unit, based on King County grading system
sqft_above - square footage of house apart from basement
sqft_basement - square footage of the basement
yr_built - Built Year
yr_renovated - Year when house was renovated
zipcode - zip
lat - Latitude coordinate
long - Longitude coordinate
sqft_living15 - The square footage of interior housing living space for the nearest 15 neighbors
sqft_lot15 - The square footage of the land lots of the nearest 15 neighbors
It is not very clear what each of them mean, but we can figure it out along the way. I have chosen to see a random sample from the dataset just so that I can be sure that the file was read correctly and to get an idea of what's going on with the data. It also helps me to check for any missing values in the dataset.
Since I can see some missing values and '?' in the data I would like to carry out more analysis to see the datatype and number of non-null values. I would also like to get a summary of all of our variables.

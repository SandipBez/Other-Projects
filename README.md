# PYTHON Projects

San Analytics has hired 10 external consultants to work on their project. As part of the financial deal, each consultant gets paid hourly. For every extra hour after 8The number of hours that the consultant has worked will be taken from the attendance register. The register marks the in and out time of each consultant from Monday to Friday. (Saturday and Sunday are holidays and any work done on these days are not considered for any extra payments.
Develop a python project to calculate the monthly payouts of each consultant, total hours worked in each month and holidays taken in each month. Also include any other calculation that you think is appropriate.

Technical implementation guidelines --

Use OOPs to develop this application
DO NOT HARDCODE attendance data
Give valid and meaningful consultant names (eg: Amit, Priya etc..). Avoid using abbreviated names like ‘abc’, ‘kri’ etc.
Take any 3 months and a year (eg: April , May, June of year 2022) to generate random register data for each consultant.
Randomly assign leaves. This is optional
Ensure proper data format for each column


# EDA PROJECT

Part 1 :
]
reate a function that will generate 'n' weather data records. The schema is as follows:

NO HARDCODING

rowid: unique record identifier

cityname: unique city name

mintemp: average minimum temperature (random integers between 5-15)

maxtemp: average maximum temperature (random integers between 25-35)

minhumid: average minimum humidity (random integers between 1-100)

maxhumid: average maximum humidity (random integers between 1-100)

alt: Altitude (random integers between 200-4000)

pollution: Pollution level (random float numbers between 1-50; 1-decimal precision)

wind dir: Wind direction (any 1 value from 'n', 's', 'w', 'e', 'ne', 'sw')

windspeed: Wind speed (random integers between 25-150)

atmpress: Atmospheric pressure (random float between 400-1200 with 1-decimal precision)

arealoc: Location (any 1 value from 'high', 'medium', 'low')

floods: Flood conditions (any 1 value from 'always', 'rarely', 'never')

visibility: Average visibility (random float between 0.25-10)

acc_due_to_fog: Accidents due to fog (random integers between 1000-15000)


Part 2

-- 2) create a dataframe to store the above details (eg df1)

-- 3) Run the function again to create a new dataframe (eg df2)

-- 4) Merge the two dataframes into a single dataframe

-- 5) write the dataframe as a CSV file

Part 3

-- 6) read the above CSV file and check contents

-- 7) check the dimensions

-- 8) check the data types of columns. Change data type wherever required

-- 9) create an index on the place name

-- 10) Check the distribution of numerical data.

-- 11) Do a statistical analysis on the numeric data and identify outliers

-- 12) For the categorical data, do an aggregation summary




Part 4 (analysis and data mining)

-- 13) Do the following analysis (write the python queries)

i) Identify the cities which always floods

ii) Which are the cities that have the highest and lowest accidents due to fog?

iii) Select the high area locations ?

iv) What is the distribution of places based on the wind direction ?

v) What is the average day temperature based on the wind direction?

vi) Select the places that have a high humidity (more than 80 )

vii) Is there a relation between pollution and elevation of a place ? Show this with a graph/chart

viii) Which are the areas that have a very low visibility (< 2 kms)?

ix) Group the data into 5 zones of atmospheric pressure and find the distribution of data .

x) Add a new column "last update" and impute it with random date for each row

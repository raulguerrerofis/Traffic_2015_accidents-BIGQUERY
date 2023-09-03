# Traffic_2015_Challenge

In this challenge I extracted from `bigquery-public-data.nhtsa_traffic_fatalities` database the table of accidents for 2015. This data is public and comes from Bigquery by using GCloud client. My steps were:

1. Extracting the data from database using SQL language
2. Transform the query to pandas dataframe
3. Separate the 10 total of fatalities in each state and in which hour (or month) the incident occurs.
4. Creating a new query for extrancting the ratio of accidents and drunken driver percentage and select the 10 biggest percentages.


-----------

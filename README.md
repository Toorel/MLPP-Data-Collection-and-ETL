# MLPP-Data-Collection-and-ETL

I used the public API that was provided by the Census Bureau. It was straightforward and instructions were provided on how to use it. Using the API, I used Washington DC and pull demographic data about data profiles that pertained to social characteristics of households. For my code, I took input from the API and transformed it into a dataframe for easy manipulation. I then used the psycopg2 to load the data into the database. 

I wrote a second script which will check if a data exists and update the row if new data is provided. The script can also insert new data into the database if necessary.



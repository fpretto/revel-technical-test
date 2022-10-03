# Analytics Engineer - Technical Test

## Overview of Datasets
-	cars_fleet.csv: fleet of cars owned by the company.
-	cars_price.csv: cars’ current market prices.
-	cars_country.csv: manufacturing region of the cars.
-	cars_trips.csv: trips made by each car in 2016.

## Tasks
1.	Using the datasets provided create a data model in a DBMS of your choice (we use PostgreSQL, but you can use whichever you prefer for this test) and load the data. Perform any transformations you consider necessary.
2.	The Operations team wants to gain insights about the usage of the cars by manufacturer (Chevrolet, Ford, VW, Dodge, etc.). This information will help them decide on which brand to focus for the next batch of cars to acquire. Particularly, they would like to know:
a.	Number of trips done by car manufacturer 
b.	Total distance travelled and average trip distance travelled by car manufacturer
c.	Average trip duration in minutes by car manufacturer
3.	The Marketing team is planning the ads budget allocation for the next semester and would like first to gather some insights on the usage of the different models. They request:
a.	They would like to focus only on models that have travelled more than 12.000 km. Which are the top 3 models for each car manufacturer, based on distance travelled?
b.	Which is the minimum, average and maximum car price for each European manufacturer and # of cylinders?
c.	They usually classify cars by their weight, in the following categories: [<1000, 1000-2000, 2000-3000, 3000-4000, 4000-5000, >5000]. They would like to you to build a matrix grouping total km travelled, having the car manufacturer as index and the weight category as columns.

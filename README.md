# Analytics Engineer - Technical Test

## Overview of Datasets
-	**cars_fleet.csv**: fleet of cars owned by the company.
-	**cars_price.csv**: cars’ current market prices.
-	**cars_country.csv**: region of the car manufacturers.
-	**cars_trips.csv**: trips made by each car in 2016.

All relevant column names are self-explanatory of the data they contain.

## Tasks
1.	Using the datasets provided create a data model in a DBMS of your choice (we use PostgreSQL, but you can use whichever you prefer for this test) and load the data. Perform any transformations you consider necessary. We would prefer it if you use Python for the ETLs.

Use SQL to answer the Operations and Marketing teams' requests:

2.	The Operations team wants to gain insights about the usage of the cars by manufacturer (Chevrolet, Ford, VW, Dodge, etc.). This information will help them decide on which brand to focus for the next batch of cars to acquire. Particularly, they would like to know:
    - Number of trips done by car manufacturer 
    - Total distance travelled and average trip distance travelled by car manufacturer
    - Average trip duration in minutes by car manufacturer

3.	The Marketing team is planning the ads budget allocation for the next semester and would like first to gather some insights on the usage of the different car models. These are the requests the team has sent you:
    - They would like to focus only on models that have travelled more than 12.000 km in total. Which are the top 3 models for each car manufacturer, based on total time travelled?
    - Which is the minimum, average and maximum car price for each European manufacturer and # of cylinders?
    - They usually classify cars by their weight, in the following categories: [<1000, 1000-2000, 2000-3000, 3000-4000, 4000-5000, >5000]. They would like to you to build a matrix grouping total km travelled, having the car manufacturer as index and the weight category as columns.

## Submission
- Submit your code via a GitHub repository shared with:
    - Fabricio Pretto: fpretto (GitHub)

- We are interested in seeing how you think, how you would approach such requests, and how you go about making technical decisions. Therefore, the overall approach taken as well as the details of your implementation will be assessed.

- We will discuss your ideas and solution together

**Happy coding!** :blush:

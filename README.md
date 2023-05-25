# nosql-challenge
Module # 12 - NoSQL Challenge

<p align="center">
<img src="images/nosql.png" alt="No SQL Graphic" width="418" height="291">
</p>

The overall objective of this challenge was to import an existing JSON dataset into a MongoDB database, make changes to the database, and then perform analysis using PyMongo. The initial dataset had to be imported via the command line using the correct commands to create the new database in MongoDB. 

Once the database was populated with the initial dataset, the next step was to make the requested transformations to meet the requirements of the 'UK Food Standards Agency'. The transformations were made using PyMongo and Jupyter Notebook.
The types of transformations included were:

-- Updating the database with a new restaurant
-- Deleting an entire region from the database
-- Changing the datatypes of specific fields for further analysis
-- Verifying the changes were made correctly

The final step was to perform analysis on the database using PyMongo and Jupyter Notebook. For each analysis, the top 10 results were returned and displayed in a dataframe. The analysis included the following.

-- Determining the number of restaurants with a hygiene score of 20
-- Determining the top rated restaurants in London, rating value >4
-- Use of aggregate pipeline queries to filter and sort the data

Using the provided analysis the food magazine 'Eat Safe, Love' can make informed decisions about which restaurants to feature in upcoming articles.



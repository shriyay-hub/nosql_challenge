Paraphrased NoSQL Challenge
Prompt:

You're tasked with analyzing food hygiene ratings data from the UK Food Standards Agency to assist a food magazine, Eat Safe, Love.

Steps:

Database Setup:

Create a MongoDB database named uk_food and a collection called establishments.
Import data from the establishments.json file into the collection.
Import necessary libraries (PyMongo, pprint).
Connect to the MongoDB instance.
Verify database and collection creation.
Database Updates:

Add a new halal restaurant to the database.
Remove establishments in Dover.
Convert certain fields (latitude, longitude, RatingValue) to appropriate data types.
Exploratory Analysis:

Answer the following questions using MongoDB queries and Pandas:
Which establishments have a hygiene score of 20?
Which London establishments have a RatingValue of 4 or higher?
Find the top 5 establishments with a RatingValue of 5, sorted by hygiene score and distance from a new restaurant.
Count establishments with a hygiene score of 0 in each Local Authority area.
Key Points:

Understand the database structure and data types.
Use MongoDB queries effectively to retrieve and manipulate data.
Convert data to Pandas DataFrames for further analysis.
Consider the meaning of different rating scores and fields.

# UK Food Standards Agency Database Analysis

# Introduction
The UK Food Standards Agency plays a crucial role in evaluating and monitoring food establishments across the United Kingdom. As part of our partnership with a food magazine, we have been tasked with analyzing the district-wide food hygiene ratings data to help the magazine's editors and food critics identify locations of interest and potential article topics.

# Part 1: Database and Jupyter Notebook Set Up
- Import the establishments data from the establishments.json file into a MongoDB database named uk_food and a collection named establishments.
- Use PyMongo to interact with the MongoDB database.
- Confirm the database and collection creation, and display one document from the establishments collection.
- Assign the establishments collection to a variable for further analysis.

# Part 2: Update the Database
- Add information for a new halal restaurant named Penang Flavours in Greenwich to the database.
- Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and update the new restaurant with the found BusinessTypeID.
- Remove any establishments within the Dover Local Authority from the database.
- Convert latitude, longitude, and RatingValue to numeric values.

# Part 3: Exploratory Analysis
Answer specific questions to help Eat Safe, Love magazine make decisions on where to focus future articles.
- Which establishments have a hygiene score equal to 20?
- Which establishments in London have a RatingValue greater than or equal to 4?
- What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
- How many establishments in each Local Authority area have a hygiene score of 0? Print out the top ten local authority areas sorted from highest to lowest.

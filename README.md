# nosql-challenge
Module 12 Challenge - NoSQL Databases


By A.Narag

March 23, 2023

This challenge has three parts:

Part 1: Database and Jupyter Notebook Set Up
See the NoSQL_setup_starter.ipynb file
  1. Import the data provided in the establishments.json file from your Terminal. Name the database uk_food and the collection establishments
  2. Within the Jupyter Notebook, import the libraries: PyMongo and Pretty Print (pprint).
  3. Create an instance of the Mongo Client.
  4. Confirm the database was created and the data loaded properly.
  5. Assign the establishments collection to a variable

Part 2: Update the Database
See the NoSQL_setup_starter.ipynb file; on this part of the challenge, we are making the following changes to the establishments collection:
  1. Include a new halal restaurant just opened in Greenwich
  2. Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields
  3. Update the new restaurant with the BusinessTypeID found
  4. Check and remove documents containining the Dover Local Authority.  Check the number of documents prior to removing to ensure all were deleted
  5. Convert number values from strings to numbers; and use update_many to convert latitude and longitude to decimal numbers

Part 3: Exploratory Analysis
See the NoSQL_analysis_starter.ipynb file; on this part of the challenge, we are using the count_documents to display the number of documents contained in the result and answering the following questions:
  1. Which establishments have a hygiene score equal to 20?
  2. Which establishments in London have a RatingValue greater than or equal to 4? 
  3. What are the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
  4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

# NOSQL-Challenge
Week 12 - No SQL Challenge

OVerview 

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

----------------------------------------------------------

Challenge

Part 1: Database and Jupyter Notebook Set Up
	1.1 Import the data provided
	1.2 Import the libraries required
	1.3 Create an instance of the Mongo Client
	1.4 Confirm the creation of database and loaded the data properly
	1.5 Assign collection to a variable to prepare the collection for use.


Part 2: Update the Database: The magazine editors have some requested modifications for the database before you can perform any queries or analysis for them
	2.1 Add the new information provided to the database
	2.2 Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.
	2.3 Update the new restaurant with the BusinessTypeID found.
	2.4 The magazine is not interested in any establishments in Dover, so check how many documents contain the Dover Local Authority. Then, remove any establishments within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted.
	2.5 Some of the number values are stored as strings, when they should be stored as numbers. Use update_many to convert latitude and longitude to decimal numbers.


Part 3: Exploratory Analysis: Eat Safe, Love has specific questions they want you to answer.
	3.1 Which establishments have a hygiene score equal to 20?
	3.2 Which establishments in London have a RatingValue greater than or equal to 4?
	3.3 What are the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
	3.4 How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

-----------------------------------------------------------
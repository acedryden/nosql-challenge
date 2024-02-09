# nosql-challenge
The purpose of this challenge is to use NoSQL, MongoDB & Pandas to import, clean and analyze data. Steps taken: 
1. Import the establishments.json file, create an instance of Mongo Client, and confirm the database was successfully created and data is loaded properly.
2. Update the database, adding a new document, retrieving the BusinessTypeID for this new restaurant from other entries, remove any documents from the Dover Local Authority and convert the data types for 3 values across the entire databuse using update_many.
3. Conduct an exploratory analysis to answer the following questions, exporting the findings into Pandas Dataframes:
   a. Which establishments have a hygiene score equal to 20?
   b. Which establishments in London have a RatingValue greater than or equal to 4?
   c. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene socre, nearest to the new restaurant added, "Penang Flavours"?
   d. How many establishments in each Local Authority area have a hygiene score of 0? Sorted from highest to lowest, print out the top ten local authority areas.  

# no-sql-challenge

This project involves evaluating food hygiene ratings across the United Kingdom using data from the UK Food Standards Agency. The goal is to assist the magazine Eat Safe, Love in identifying establishments for future articles. The project is conducted using MongoDB and Python within Jupyter Notebook.

Part 1: Database and Jupyter Notebook Setup

Imported data from establishments.json into MongoDB, creating the uk_food database and the establishments collection.

Connected to MongoDB using PyMongo and verified successful data import.

Retrieved sample data to confirm database setup.

Part 2: Database Updates

Added a new restaurant, Penang Flavours, in Greenwich that hasn't been rated yet.

Identified and updated the BusinessTypeID for "Restaurant/Cafe/Canteen."

Removed all establishments under the Dover Local Authority.

Converted latitude, longitude, and RatingValue fields to appropriate numeric types.

Part 3: Exploratory Analysis

Performed data queries to answer key questions for the magazine:

Identified establishments with a hygiene score of 20.

Found establishments in London with a rating of 4 or higher.

Located the top 5 establishments rated 5, sorted by lowest hygiene score, near Penang Flavours.

Aggregated and ranked Local Authority areas with the most establishments having a hygiene score of 0.

Technologies Used

MongoDB (NoSQL Database)

PyMongo (MongoDB Python Client)

Pandas (Data Analysis)

Jupyter Notebook (Data Exploration)

This analysis provides insights that Eat Safe, Love can use for feature articles and reviews. The dataset has been cleaned and updated to improve data integrity and usability.

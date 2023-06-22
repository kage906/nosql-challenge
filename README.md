# Exploring UK Food Standards Agency's Hygiene Ratings with NoSQL
![Food-Safety](https://user-images.githubusercontent.com/52866379/230804218-7b207988-39da-4931-9349-e81738c18d31.png)

# Introduction:
In this project, I was contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data from the UK Food Standards Agency. The goal was to help their journalists and food critics decide where to focus future articles. The data was provided in a JSON format file and MongoDB was used as the NoSQL database to store and manage the data. This project involved setting up the database, updating it, and performing exploratory analysis on the data.

# Project Overview:
The project consisted of three parts:

* Part 1: Setting up the database and Jupyter Notebook
* Part 2: Updating the database
* Part 3: Exploratory Analysis

# What I Did:
In Part 1, I used the PyMongo library to import the data from the establishments.json file and set up the MongoDB client. I then checked the data by finding and displaying one document from the establishments collection.

In Part 2, I added a new restaurant and updated its BusinessTypeID. I also deleted establishments from a specific local authority, and converted string values to numbers.

In Part 3, I performed exploratory analysis on the data by answering four specific questions using PyMongo queries. I used various methods like count_documents, pprint, and aggregation pipeline to find the answers. I also converted the results into pandas dataframes for better visualization.

# Tools Used:
* Jupyter Notebook
* Python
* PyMongo
* MongoDB
* Pandas

# What I Learned:
Through this project, I learned how to work with NoSQL databases like MongoDB, and how to manipulate and analyze data using PyMongo. I also learned how to perform basic CRUD operations on MongoDB, including creating, reading, updating, and deleting data. Additionally, I learned how to use various methods in PyMongo to perform complex queries and aggregations.

# Conclusion:
This project provided me with a valuable learning experience in working with NoSQL databases and PyMongo. It also allowed me to explore the hygiene ratings data provided by the UK Food Standards Agency and answer specific questions based on the data. Overall, this project enhanced my skills in data manipulation, analysis, and visualization.

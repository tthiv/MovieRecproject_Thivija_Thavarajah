Thivija Thavarajah


Project: Movie Reccomender


This file contains:

1. Project.ipynb -> contains the python code that calculates cosine and utility to get the recommended movies

2. test.html -> contains the html code that gets user input, this outputs userRate.xlxs


3.Main.css -> formatting for the html code

4. Ml-latest-small -> stores the movie database and also where the user rated movie excel sheet is stored.

5. Final Project Report



Movie Recommender
This file contains the HTML code for the websites where user can input the films they watched and rate it. It exports the completed table into a excel file (.xlxs).
project.ipynb

This file contains the python code that analyses the movie database and the user rated excel file to recommend.

The first part of the program gets the movie database and formats it by removing unnecessary columns and formatting the empty rows. It also gets the excel sheet of the user rated films as well.

The second one gets the cosine score for the most similar users. After getting the cosine score, we sort it in descending order and get the top 6 users. After that we analyse what movies they watched and get the utility score and recommend the highest rated movie for that. And then we output the table with the top 10 recommended movies.
test.html

How To Run The Program
Open up test.html first and input the movies and their rates, then click the add movies to add the values into the table. Then click export to excel to get the excel file. Move the file into the project folder.

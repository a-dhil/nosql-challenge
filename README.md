# nosql-challenge

GitHub Repo Link: https://github.com/a-dhil/nosql-challenge
Folder Resolurces: contains file name establishments.json 
Folder food_hygiene_rating: contains files with name NoSQL_analysis_starter.ipynb, NoSQL_setup_starter.ipynb

# About Challenge

The UK Food Standars Agency, in UK evalutes different etsablishments and provides then rating in food hygiene.

In this challenge the editors of the magzine, Eat, Safe, Love wants to evaluate rating data in order to guide journalists to focous future articles.

Skills required to do this challenge are MongoDB, Python

Part 1

In terminal run this command
'Import the dataset with mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json'


NoSQL_setup_starter.ipynb file is used for this part to setup a database. Once date was set up it was edited by adding new restaurant "Panang Flavours" and deleting Dover Local Authority documents as per clients requirements.

Part 2

In this exploratory analysis  NoSQL_analysis_starter.ipynb file was used.

The question were:

Q. Which establishments have a hygiene score equal to 20?


Q. Which establishments in London have a RatingValue greater than or equal to 4?


Q.What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the "Penang Flavours"?

Q.How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

To answer these questions quereis were created using operators like $regex, $gte, $lte, $eq etc.

In the end the results were tranfered into pandas Data Frames.

# Acknowldgments

This is to acknowledge that myself Angaddeep has completed this assignment with the help of ASK BCS learning assistance and Tutor. 
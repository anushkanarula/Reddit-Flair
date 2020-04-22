# Reddit-Flair
A Reddit Flair web application to detect flairs of India subreddit posts using Machine Learning algorithms.

Structure
The directory largely contains 2 ipython notebooks and 1 web directory:
Data-scraping Notebook contains all the code that was used to fetch data using PRAW API from reddit and adding it to the mongodb database using pymongo. It was the fetched back from the data base and pre-processed to add it into a CSV file to do the data analysis and build the machine learning model.
Flair-detection Notebook contains the code used to do the data analysis and train various machine learning models and check the accuracy on different features.
Website Directory the directory contains the flask implementation of the app and the requirements and procfile for heroku deployment. The detail of each file in the directory can be found in the readme.md file of the directory.

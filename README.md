# Reddit-Flair
A Reddit Flair web application to detect flairs of India subreddit posts using Machine Learning algorithms.

Structure

The directory largely contains 2 ipython notebooks and 1 web directory:
Data-scraping Notebook contains all the code that was used to fetch data using PRAW API from reddit and adding it to the mongodb database using pymongo. It was the fetched back from the data base and pre-processed to add it into a CSV file to do the data analysis and build the machine learning model.
Flair-detection Notebook contains the code used to do the data analysis and train various machine learning models and check the accuracy on different features.
Website Directory the directory contains the flask implementation of the app and the requirements and procfile for heroku deployment. The detail of each file in the directory can be found in the readme.md file of the directory.

Codebase

The entire code has been developed using Python programming language, utilizing it's powerful text processing and machine learning modules. The application has been developed using Flask web framework and hosted on Heroku web server.

References

1. For data collection:
http://machineloveus.com/mining-reddit-data-or-links-to-33-python-cheat-sheets/
http://www.storybench.org/how-to-scrape-reddit-with-python/
https://towardsdatascience.com/scraping-reddit-data-1c0af3040768
https://api.mongodb.com/python/current/tutorial.html

2. For Building machine learning model:
https://medium.com/themlblog/splitting-csv-into-train-and-test-data-1407a063dd74
https://towardsdatascience.com/multi-class-text-classification-model-comparison-and-selection-5eb066197568
https://medium.com/@robert.salgado/multiclass-text-classification-from-start-to-finish-f616a8642538
https://www.analyticsvidhya.com/blog/2018/04/a-comprehensive-guide-to-understand-and-implement-text-classification-in-python/

3.For Deploying the model:
https://medium.com/techkylabs/getting-started-with-python-flask-framework-part-1-a4931ce0ea13 (entire series)
https://towardsdatascience.com/designing-a-machine-learning-model-and-deploying-it-using-flask-on-heroku-9558ce6bde7b
https://www.freecodecamp.org/news/how-to-build-a-web-application-using-flask-and-deploy-it-to-the-cloud-3551c985e492/
https://hackernoon.com/deploy-a-machine-learning-model-using-flask-da580f84e60c
https://blog.cambridgespark.com/deploying-a-machine-learning-model-to-the-web-725688b851c7

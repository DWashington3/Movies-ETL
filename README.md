# Cleaning Movie Data using SQLAlchemy 
## Overview
An online retailer needs to develop an algorithm that will find low-budget movies that become popular. These movies that qualify will be purchased for steaming rights on their platform. I've been asked to create the datasets from information scraped from Kaggle and Wikipedia. The final datasets will be used for the hackathon. 
### Preprocessing
To create the datasets I first scrapped the data from Wikipedia and Kaggle movie data sets provided online. After extraction, I did a general overview of the data by converting flat files into pandas Dataframes and converting the Wikipedia data into a data frame. Next, I started the interactive processes of cleaning the data by identifying relevant columns using list comprehensions to filter data. I created my own functions to clean each dataset iterative. Lastly, to modify the formats of the outputs in the data frame I used Regular Expression to ensure the formats were correct for the contents of the column. Lastly, I merged the two sets to provide a useful summary of information for the hackathon which was done by importing the pandas data frame to SQL.
## Results
##
## Conlusion

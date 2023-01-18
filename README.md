## Recommendations with IBM

### Project Motivation:
#### The idea of this project to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they possibly will like. Below is an example of what the dashboard could look like displaying articles on the IBM Watson Platform.

![IBM-Watson-Scr](https://user-images.githubusercontent.com/42642798/213243300-cf51a1ce-57cd-4f2e-8bea-6473d5bd435b.jpg)

### File Details:
#### data/user-item-interactions.csv
#### data/articles_community.csv
#### Recommendations_with_IBM.ipynb
#### Recommendations_with_IBM.html
#### Recommendations_with_IBM.pdf
#### project_tests.py
#### README.md

### Methodology Used
#### Part I  : Exploratory Data Analysis - Bring out the details of the data from the .csv files and explore few statistical details.  
#### Part II : Rank-Based Recommendations - Here we ned to find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).
#### Part III: User-User Based Collaborative Filtering - Here we need to look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.
#### Part IV : Matrix Factorization - Content Based Recommendations (EXTRA - NOT REQUIRED) - Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using the NLP skills, we need to develop a content based recommendation system.
#### Part V  : Matrix Factorization - Matrix factorization should be done here to make article recommendations to the users on the IBM Watson Studio platform.
Finally, a machine learning approach should be utilized to build recommendations. Using the user-item interactions, we need to build out a matrix decomposition. Using the decomposition, we need get an idea of how well the predictions are. 

### Libraries Used
#### numpy
#### pandas
#### matplotlib.pyplot
#### project_tests
#### pickle
#### call from subprocess
#### itertools

### Acknowledgements
#### Dataset Credit - Udacity
#### Others: Thanks to Udacity for excellent course material and also to the mentors for timely help.

### Acknowledgements
#### Dataset Credit - https://www.kaggle.com/airbnb/seattle
#### Others: Thanks to Udacity for excellent course material and also to the mentors for timely help.

## Recommendations with IBM

### Project Motivation:
#### The main idea of this project is to find out if there a way to find out a set of features which can help to predict the price of airbnb homestay. Analysis was done around various features like neighborhod, property type, room type and amenities etc. Later on focus was on a smaller set of features which can help to predict the price.

### File Details:
#### data/user-item-interactions.csv
#### data/articles_community.csv
#### Recommendations_with_IBM.ipynb
#### Recommendations_with_IBM.html
#### Recommendations_with_IBM.pdf
#### project_tests.py
#### README.md

### Methodology Used
#### Part I  : Exploratory Data Analysis - Bring out the details of the data from the .csv file and explore few statistical details.  
#### Part II : Rank-Based Recommendations - Need not ratings for whether a user liked an article or not.It is only know that a user has interacted with an article. In these cases, the popularity of an article can really only be based on how often an article was interacted with.
#### Part III: User-User Based Collaborative Filtering should be done here. Utilizing the function provided in this section the df dataframe to be reformat with users as the rows and articles as the columns.
#### Part IV : Matrix Factorization - Content Based Recommendations (EXTRA - NOT REQUIRED)
#### Part V  : Matrix Factorization - Matrix factorization should be done here to make article recommendations to the users on the IBM Watson Studio platform.

### Libraries Used
#### numpy
#### pandas
#### matplotlib.pyplot
#### project_tests
#### pickle
#### call from subprocess
#### itertools

### Acknowledgements
#### Dataset Credit - https://www.kaggle.com/airbnb/seattle
#### Others: Thanks to Udacity for excellent course material and also to the mentors for timely help.

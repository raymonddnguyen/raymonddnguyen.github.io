# Data Science Portfolio by Raymond Nguyen
This portfolio is a compilation of notebooks and projects that I have made for data analysis and machine learning.

### Live Anime Twitter Sentiment Analysis
I used Twitter’s python API, Tweepy to stream live tweets to predict positive (1) or negative (0) sentiment using an LSTM-CNN with GLoVe embedding network using Keras. Validation accuracy of final model improved from 78% using a Bag-of-Words method to 84% using the GLoVe embedded LSTM-CNN model.

<a href='https://github.com/raymonddnguyen/Twitter-Sentiment-Analysis/blob/master/anime_twitter_sentiment_analysis.ipynb'>Github</a>
<a href='https://nbviewer.jupyter.org/github/raymonddnguyen/Twitter-Sentiment-Analysis/blob/master/anime_twitter_sentiment_analysis.ipynb'>nbviewer</a>

### Predicting French Nutritional Health Grades
Collaborated in a group to predict food nutrition grades based on the National French Nutrition Score (Grades A - E) with a 90% accuracy. We used the <a href='https://www.nutritionix.com/'>Nutrionix API</a> to grab nutrients such as protein, sodium, and saturated fats for live prediction of food grades with a Random Forest model.  The data was grabbed from <a href='https://www.kaggle.com/openfoodfacts/world-food-facts/data'>OpenFoodFacts</a>, a free, online and crowdsourced database of food products.  

<a href='https://github.com/raymonddnguyen/Predicting-Food-Grades'>Github</a>

### Predicting Device Failures
I worked with an anonymized imbalanced dataset in order to predict device failures.  The notebook includes my exploratory data analysis and feature engineering.  I used ADASYN as my method of oversampling.  My final model was an ensemble of random forest, KNN, SVC, extra trees, and XGBoost.  I improved the precision and recall to 88% and 83% respectively while maintaining an overall 98% accuracy.

<a href='https://github.com/raymonddnguyen/Notebooks/blob/master/Device%20Failures/Device_Failures.ipynb'>Github</a>
<a href='https://nbviewer.jupyter.org/github/raymonddnguyen/Notebooks/blob/master/Device%20Failures/Device_Failures.ipynb'>Nbviewer</a>

### Health Product Recommendation System
Using Pandas, Numpy, Seaborn & Scikit-Learn, analyzed data to reveal information about KPI’s such as item purchases, popularity, and profit. Product recommendations were made implicitly using item quantities based on alternating least squares and SVD.

<a href='https://github.com/raymonddnguyen/Notebooks/blob/master/Health%20Product%20Recommendation%20Systems/recommendation_system.ipynb'>Github</a>
<a href='https://nbviewer.jupyter.org/github/raymonddnguyen/Notebooks/blob/master/Health%20Product%20Recommendation%20Systems/recommendation_system.ipynb'>Nbviewer</a>

### Titanic: Machine Learning from Disaster
Titanic: Machine Learning from Disaster is widely considered to be the "Hello World" project of Data Science and it was my introduction also.  The data and information can be found <a href='https://www.kaggle.com/c/titanic'>here</a>.  I was able to score within the top 2% with some feature engineering and KNN.

<a href='https://github.com/raymonddnguyen/Notebooks/blob/master/Titanic/Titanic.ipynb'>Github</a> <br>
<a href='https://nbviewer.jupyter.org/github/raymonddnguyen/Notebooks/blob/master/Titanic/Titanic.ipynb'>Nbviewer</a>

### Predicting Poverty
Analyzed and predicted an anonymized/encoded dataset in order to predict poverty in a given country.  The idea in doing this was to practice basic machine learning fundamentals given zero domain knowledge.  Best performing model used was XGBoost with a log-loss ratio of 0.257.

<a href='https://github.com/raymonddnguyen/Notebooks/blob/master/Poverty/Poverty_Classification.ipynb'>Github</a> <br>
<a href='https://nbviewer.jupyter.org/github/raymonddnguyen/Notebooks/blob/master/Poverty/Poverty_Classification.ipynb'>Nbviewer</a>

## Data Collection

### Macy's Web Scraper
I collected a list of items and prices from Macy's using BeautifulSoup and Requests.  There were about 50,000 items and I missed about 2 brands.

<a href="https://github.com/raymonddnguyen/Notebooks/blob/master/Webscraping/Macy's/macys_web_scrape.py">Github</a>
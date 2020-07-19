# Data Science and  Analytics Projects
This portfolio consists of several data science and anaytics projects illustrating the work I have done in order to further develop my data science skills.
# Table of Contents
1. Python 
  * Financial Crime Fraud Analytics
2. R 
3. SAS
4. Visualizations (PowerBI, Tablueau, ScatterText)
5. Model Deployment 

# Projects
## Python
### 1. Financial Crime Fraud Analytics
[Repository](https://github.com/wandabwa2004/Fraud_Analytics) | [Notebook](https://github.com/wandabwa2004/Fraud_Analytics/blob/master/Fraud%20Detection%20.ipynb) | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/Fraud_Analytics/blob/master/Fraud%20Detection%20.ipynb)
* Descriptive and Predictive Analytics for a Synthetic dataset on Financial crimes. 
* The dataset https://www.kaggle.com/ntnu-testimon/paysim1/download is a synthetic one i.e. simulated using PaySim based on a sample of real transactions extracted from one month of financial logs from a mobile money service implemented in an African country. The dataset is scaled down 1/4 of the original dataset.
* Used [sweetviz](https://pypi.org/project/sweetviz/) package for  Exploratory Data Analysis (EDA).
* Identified the  most probable fraud  indicators.
* XGBoost and  RandomForest Classifiers with Area under the precision-recall curve (AUPRC) as the  metric  for the skewed dataset.

![Correlation Plot for Different Factors in Financial Crime](https://github.com/wandabwa2004/Fraud_Analytics/blob/master/fraud_analytics.png "Correlation of factors in financial crime")

### Conclusion:
1. Fraud detection is a difficult process. This is especially compounded by the lack of integral data in the area.
2. Tree based algorithms worked better in detection of fraud. This is partly attributed to the nature of data.

### 2. Fitbit Data Analytics during  COVID-19 Lockdown in New Zealand
[Repository](https://github.com/wandabwa2004/Fitbit-Analytics-Lockdown/) | [Notebook](https://github.com/wandabwa2004/Fitbit-Analytics-Lockdown/blob/master/Fitbit%20Analytics%20-%20Lockdown.ipynb) | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/Fitbit-Analytics-Lockdown/blob/master/Fitbit%20Analytics%20-%20Lockdown.ipynb) | [Blog Article](https://medium.com/swlh/6-kgs-lost-in-31-days-of-covid-19-lockdown-a-data-analytics-perspective-a0061e0689f2?source=friends_link&sk=7c19969f1c54fb013d3cdae45319d78d)
* Analytics of my body, activity and sleep data during the COVID-19 lockdown. 
* Identification of important factors that necessitated weight loss during the lockdown time. 
![Fitbit Data Analytics](https://github.com/wandabwa2004/Fitbit-Analytics-Lockdown/blob/master/fitbit.png "Fitbit Data Analytics")

### 3. NLP: Tweeting patterns during  COVID-19 Lockdown in New Zealand 
[Repository](https://github.com/wandabwa2004/COVID-19-Lockdown) | [Notebook](https://github.com/wandabwa2004/COVID-19-Lockdown/blob/master/COVID-19%20Lockdown%20Tweeting.ipynb) | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/COVID-19-Lockdown/blob/master/COVID-19%20Lockdown%20Tweeting.ipynb)
* Collection of streaming tweets from Auckland and Wellington, New Zealand's largest cities during  COVID-19 Lockdown period. 
* Descriptive analytics on the tweeting patterns by users from the  two cities. Aucklanders seemed to work more than tweet. 
* Topics of discussion were  semantically identical across the cities. Visualized by PyLDAVis.

![Tweeting  Patterns during  COVID-19 Lockdown](https://github.com/wandabwa2004/COVID-19-Lockdown/blob/master/tweeting%20_covid.png "COVID-19 Tweeting Patterns  in NZ")

### 4. Sea Turtle Rescue Forecast Challenge. 
[Repository](https://github.com/wandabwa2004/sea-turtle-forecast-challenge) | [Notebook](https://github.com/wandabwa2004/sea-turtle-forecast-challenge/blob/master/Sea%20Turtle%20Rescue%20Forecast%20Challenge.ipynb) | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/sea-turtle-forecast-challenge/blob/master/Sea%20Turtle%20Rescue%20Forecast%20Challenge.ipynb)

The objective of the competition is to create a machine learning model to help Kenyan non-profit organization Local Ocean Conservation anticipate the number of turtles they will rescue from each of their rescue sites as part of their By-Catch Release Programme https://zindi.africa/competitions/sea-turtle-rescue-forecast-challenge.
* Descriptive analytics and  EDA for the dataset. Included encoding etc for better modelling. 
* 1.1897261428182493 RMSE as the measurement metric. 

![Turtles Capture and  Release Programme](https://github.com/wandabwa2004/sea-turtle-forecast-challenge/blob/master/turtles.png "Captured Numbers/Year")


### 5. Bidirectional Encoder Representations from Transformers (BERT) in computation of a few African Cities Happiness. 
[Repository](https://github.com/wandabwa2004/BERT_Happiness_Index) | [Notebook](https://github.com/wandabwa2004/BERT_Happiness_Index/blob/master/BERT-%20Happiness2.ipynb) | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/BERT_Happiness_Index/blob/master/BERT-%20Happiness2.ipynb) | [Blog Article](https://towardsdatascience.com/kigali-the-2019-happiness-capital-a0085dc1efc4?source=friends_link&sk=4ea0299439406d885c6c4d758f630643)
* Collection of  tweets from the different cities via geocoding. 
* Translation via  GoogleTranslate Python library for modelling.
* Descriptive analytics of the datasets per country. 
* Modelling  via  BERT and batch sentiment prediction per tweet and grouped by cities. 
* The highest probability to a sentiment was assumed to be the true sentiment of the  tweet. 

![BERT Happiness Index](https://github.com/wandabwa2004/BERT_Happiness_Index/blob/master/berthappiness.PNG "BERT Happiness Index for a few African Cities")

### 6. Te Papa Tongarewa (Museum of New Zealand) Sentimental Footing. 
[Article](https://towardsdatascience.com/te-papa-tongarewa-museum-of-new-zealand-sentimental-footing-d062e41e430f?source=friends_link&sk=2f0c07b247153effb1639d5193a898d3)

Code Snippets with:-
* Descriptive Analytics of  Trip Advisor reviews for Museum of New Zealand (Te Papa Tongarewa)
* Sentiment  Analysis of the reviews.

![Sentiment Over Time](https://miro.medium.com/max/700/1*neOrnIcTZEMh5KW0f6jupA.png "Te Papas Sentiments over Time")

### 7. We are just a Loquacious lot. 2019 Kenyan Social Beat 
[Article](https://medium.com/@hermanwandabwa/we-are-just-a-loquacious-lot-2019-kenyan-social-beat-458938d5a066?source=friends_link&sk=a8d224ee3022decff6b78a4b5f9f8846)
The project was an anlytical piece about what Kenyans really discuss online. Data in form of  tweets was from January to December 2019. 

Questions of Interest:-
1. Are we able to deduce the nature of Kenyans based on their daily chatter? Do they talk about substantive issues?
2. Are they topically consistent in their talk over time?

![Nairobi City from the Space Station](https://miro.medium.com/max/700/1*L5nAfujAwemq-4f1eThOFg.jpeg "Nairobi City at night as  viewed from the International Space Station")







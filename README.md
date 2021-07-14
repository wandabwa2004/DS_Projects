# Data Science and  Analytics Projects
This portfolio consists of several data science and anaytics projects illustrating the work I have done in order to further develop my data science skills.
# Table of Contents
### 1. Python 
  * [Online Sharepoint 365  Uploader](#sharepointuploader)
  * [Financial Crime Fraud Analytics](#financialscrime)
  * [Political Content Sentiment Analyzer](#politicalsentiment)
  * [Fitbit Data Analytics during COVID-19 Lockdown in New Zealand](#fitbit)
  * [NLP: Tweeting patterns during COVID-19 Lockdown in New Zealand](#covid_tweeting)
  * [Sea Turtle Rescue Forecast Challenge](#sea_turles)
  * [Bidirectional Encoder Representations from Transformers (BERT) in computation of a few African Cities Happiness](#bert_happiness)
  * [Te Papa Tongarewa (Museum of New Zealand) Sentimental Footing](#tepapa_sentiments)
  * [We are just a Loquacious lot. 2019 Kenyan Social Beat](#loquacious)
### 2. R 
  * [Emotion Detection in New Zealander's Tweets  Over the COVID-19 Lockdown Period](#emotions)
  * [Speech Analytics: State of the Nation Addresses by Kenya's President, Uhuru Kenyatta](#speech_analytics)
### 3. SAS
  * [Black Friday Sales Analytics](#black_friday)
### 4. Visualizations (PowerBI, Tablueau, ScatterText)
  * [PowerBI: Coronavirus numbers as at 10/03/2020](#covid_powerBI)
  * [ScatterText: Museum of  New Zealand Reviews TripAdvisor Reviews and Related Topics](#scatter_tepapa)
### 5. Model Deployment 
  * [Kenyan Political Sentiments Monitor - The Polimeter](#deployment_political)
### 6. [Data  Science and Engineering  Certifications](#ds_eng)
### 7. [Publications](#publications) 

# Projects
## Python
<h2>  <a id="sharepointuploader" href="https://github.com/wandabwa2004/SharepointUploader"> 1.Sharepoint 365 Uploader </a> </h2>
[Repository](https://github.com/wandabwa2004/SharepointUploader) 
![SharepointUploader](https://user-images.githubusercontent.com/8840942/125596131-b59d8c47-7aae-4d8b-ba10-d497db65f333.JPG)
Tool designed and developed using Python and Streamlit to help you upload files to an online Sharepoint location. This works with Sharepoint 365 but can be modified to fit earlier SharePoint versions.Current functionality includes:

* Specifying the folder path to the files to be  uploaded (Source URL).
* Summary information of the files to be  uploaded. 
* Specification of Sharepoint login and related upload details. 
* Creation of  a folder based on the todays date format in the base URL that is user specified.
* Upload of the files matching  the  specified extension (currently .xlsx) to the  new folder in the base URL. File format can be changed

## Notes on Usage
* A deployed version of  the app can be found here https://sharepointuploader.herokuapp.com/. The app can also be cloned and run locally using streamlit: `streamlit run SharepointUploader.py`. When doing this, ensure you have the required modules listed in the requirements file.
* Make sure  the account  details for  accessing  Sharepoint on your  domain are valid. Normally, the username  is your domain specific email and password. 

## Bugs, Enhancements and Comments
All comments, bug reports and enhancement requests are welcome. To do so, please submit a new issue and I will work hard on improving the app. 

## Future Functionality
Future functionality will likely include:
* Option to specify the file formsts  to be uploaded in a folder with mixed file types. 
* Email trigger to the  username once  the files are all uploaded. 

<h2>  <a id="financialscrime" href="https://github.com/wandabwa2004/Fraud_Analytics"> 1.Financial Crime Fraud Analytics </a> </h2>

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

<h2>  <a id="politicalsentiment" href="https://github.com/wandabwa2004/sent_analyzer_kenya"> 2. Political Content Sentiment Analyzer </a> </h2>

In this  project, I setup a tweets  collection framework for tweets belonging to five politicians in Kenya. I analyzed the tweet sentiments/emotions over time, packaged the same in a Streamlit App and hosted the same on Heroku. 

[Code](https://github.com/wandabwa2004/sent_analyzer_kenya) | [Deployed App](https://sentiment-politics-kenya.herokuapp.com/)

<h2>  <a id="fitbit" href="https://github.com/wandabwa2004/Fitbit-Analytics-Lockdown/"> 3. Fitbit Data Analytics during  COVID-19 Lockdown in New Zealand </a> </h2>

[Repository](https://github.com/wandabwa2004/Fitbit-Analytics-Lockdown/) | [Notebook](https://github.com/wandabwa2004/Fitbit-Analytics-Lockdown/blob/master/Fitbit%20Analytics%20-%20Lockdown.ipynb) | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/Fitbit-Analytics-Lockdown/blob/master/Fitbit%20Analytics%20-%20Lockdown.ipynb) | [Blog Article](https://medium.com/swlh/6-kgs-lost-in-31-days-of-covid-19-lockdown-a-data-analytics-perspective-a0061e0689f2?source=friends_link&sk=7c19969f1c54fb013d3cdae45319d78d)
* Analytics of my body, activity and sleep data during the COVID-19 lockdown. 
* Identification of important factors that necessitated weight loss during the lockdown time. 
![Fitbit Data Analytics](https://github.com/wandabwa2004/Fitbit-Analytics-Lockdown/blob/master/fitbit.png "Fitbit Data Analytics")

<h2>  <a id="covid_tweeting" href="https://github.com/wandabwa2004/COVID-19-Lockdown"> 4. NLP: Tweeting patterns during  COVID-19 Lockdown in New Zealand </a> </h2>

[Repository](https://github.com/wandabwa2004/COVID-19-Lockdown) | [Notebook](https://github.com/wandabwa2004/COVID-19-Lockdown/blob/master/COVID-19%20Lockdown%20Tweeting.ipynb) | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/COVID-19-Lockdown/blob/master/COVID-19%20Lockdown%20Tweeting.ipynb)
* Collection of streaming tweets from Auckland and Wellington, New Zealand's largest cities during  COVID-19 Lockdown period. 
* Descriptive analytics on the tweeting patterns by users from the  two cities. Aucklanders seemed to work more than tweet. 
* Topics of discussion were  semantically identical across the cities. Visualized by PyLDAVis.

![Tweeting  Patterns during  COVID-19 Lockdown](https://github.com/wandabwa2004/COVID-19-Lockdown/blob/master/tweeting%20_covid.png "COVID-19 Tweeting Patterns  in NZ")

<h2>  <a id="sea_turles" href="https://github.com/wandabwa2004/sea-turtle-forecast-challenge"> 5. Sea Turtle Rescue Forecast Challenge </a> </h2>

[Repository](https://github.com/wandabwa2004/sea-turtle-forecast-challenge) | [Notebook](https://github.com/wandabwa2004/sea-turtle-forecast-challenge/blob/master/Sea%20Turtle%20Rescue%20Forecast%20Challenge.ipynb) | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/sea-turtle-forecast-challenge/blob/master/Sea%20Turtle%20Rescue%20Forecast%20Challenge.ipynb)

The objective of the competition was to create a machine learning model to help Kenyan non-profit organization Local Ocean Conservation anticipate the number of turtles they will rescue from each of their rescue sites as part of their By-Catch Release Programme https://zindi.africa/competitions/sea-turtle-rescue-forecast-challenge.
* Descriptive analytics and  EDA for the dataset. Included encoding etc for better modelling. 
* 1.1897261428182493 RMSE as the measurement metric. 

![Turtles Capture and  Release Programme](https://github.com/wandabwa2004/sea-turtle-forecast-challenge/blob/master/turtles.png "Captured Numbers/Year")

<h2>  <a id="bert_happiness" href="https://github.com/wandabwa2004/BERT_Happiness_Index"> 6. Bidirectional Encoder Representations from Transformers (BERT) in computation of a few African Cities Happiness </a> </h2>

[Repository](https://github.com/wandabwa2004/BERT_Happiness_Index) | [Notebook](https://github.com/wandabwa2004/BERT_Happiness_Index/blob/master/BERT-%20Happiness2.ipynb) | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/BERT_Happiness_Index/blob/master/BERT-%20Happiness2.ipynb) | [Blog Article](https://towardsdatascience.com/kigali-the-2019-happiness-capital-a0085dc1efc4?source=friends_link&sk=4ea0299439406d885c6c4d758f630643)
* Collection of  tweets from the different cities via geocoding. 
* Translation via  GoogleTranslate Python library for modelling.
* Descriptive analytics of the datasets per country. 
* Modelling  via  BERT and batch sentiment prediction per tweet and grouped by cities. 
* The highest probability to a sentiment was assumed to be the true sentiment of the  tweet. 

![BERT Happiness Index](https://github.com/wandabwa2004/BERT_Happiness_Index/blob/master/berthappiness.PNG "BERT Happiness Index for a few African Cities")

<h2>  <a id="tepapa_sentiments" href="https://towardsdatascience.com/te-papa-tongarewa-museum-of-new-zealand-sentimental-footing-d062e41e430f?source=friends_link&sk=2f0c07b247153effb1639d5193a898d3"> 7. Te Papa Tongarewa (Museum of New Zealand) Sentimental Footing</a> </h2>

[Article](https://towardsdatascience.com/te-papa-tongarewa-museum-of-new-zealand-sentimental-footing-d062e41e430f?source=friends_link&sk=2f0c07b247153effb1639d5193a898d3)

Code Snippets with:-
* Descriptive Analytics of  Trip Advisor reviews for Museum of New Zealand (Te Papa Tongarewa)
* Sentiment  Analysis of the reviews.

![Sentiment Over Time](https://miro.medium.com/max/700/1*neOrnIcTZEMh5KW0f6jupA.png "Te Papas Sentiments over Time")

<h2>  <a id="loquacious" href="https://medium.com/@hermanwandabwa/we-are-just-a-loquacious-lot-2019-kenyan-social-beat-458938d5a066?source=friends_link&sk=a8d224ee3022decff6b78a4b5f9f8846"> 8. We are just a Loquacious lot. 2019 Kenyan Social Beat </a> </h2>

[Article](https://medium.com/@hermanwandabwa/we-are-just-a-loquacious-lot-2019-kenyan-social-beat-458938d5a066?source=friends_link&sk=a8d224ee3022decff6b78a4b5f9f8846)

The project was an anlytical piece about what Kenyans really discuss online. Data in form of  tweets was from January to December 2019. 

Questions of Interest:-
1. Are we able to deduce the nature of Kenyans based on their daily chatter? Do they talk about substantive issues?
2. Are they topically consistent in their talk over time?

![Nairobi City from the Space Station](https://miro.medium.com/max/700/1*L5nAfujAwemq-4f1eThOFg.jpeg "Nairobi City at night as  viewed from the International Space Station")

## R
<h2>  <a id="emotions" href="https://github.com/wandabwa2004/EmotionDetetection">1. Emotion Detection in New Zealander's Tweets  Over the COVID-19 Lockdown Period </a> </h2>

[Repository](https://github.com/wandabwa2004/EmotionDetetection) | [Code](https://github.com/wandabwa2004/EmotionDetetection/blob/master/EmotionsDetection.R) 

* Descriptive Analytics of tweets geolocated to New Zealand. 
* Emotions Analysis in the collected tweets

![Emotions Distribution](https://github.com/wandabwa2004/EmotionDetetection/blob/master/emotions.jpg "New Zealander's Emotions During  COVID-19 Lockdown period")

<h2>  <a id="speech_analytics" href="https://github.com/wandabwa2004/StateoftheUnionAddresses_UK"> 2. Speech Analytics: State of the Nation Addresses by Kenya's President, Uhuru Kenyatta </a> </h2>

[Repository](https://github.com/wandabwa2004/StateoftheUnionAddresses_UK) | [Code](https://github.com/wandabwa2004/StateoftheUnionAddresses_UK/blob/master/Uhuru.R)  [Blog Article](https://towardsdatascience.com/uhuru-kenyattas-2019-state-of-the-nation-address-most-positive-557d9cfb3f13?source=friends_link&sk=051b33656754906e8cd95c6182c693da)

* Descriptive Analytics of Uhuru Kenyatta's State of  the  Nation speeches from 2014 - 2019. 
* The language in Uhuru Kenyatta's State of the Nation addresses from 2014-2019 never changed.
* His 2015's speech was the most difficult in terms of readability i.e. needed someone at postgraduate/ advanced undergraduate level to read and probably understand.
* His 2019 speech was the most positive of all his speeches

![Polarity in the speeches over time](https://github.com/wandabwa2004/StateoftheUnionAddresses_UK/blob/master/speeches.png "Polarity in Uhuru Kenyatta's Speeches between 2014 - 2019")

## SAS
<h2>  <a id="black_friday" href="https://github.com/wandabwa2004/SAS_Sales_Analysis/"> 1. Black Friday Sales Analytics  </a> </h2>

[Repository](https://github.com/wandabwa2004/SAS_Sales_Analysis/) | [Code](https://github.com/wandabwa2004/SAS_Sales_Analysis/blob/master/BlackFriday.sas) | [Dataset](https://github.com/wandabwa2004/SAS_Sales_Analysis/blob/master/BlackFriday.csv) | [Analytics Output](https://github.com/wandabwa2004/SAS_Sales_Analysis/blob/master/Sales%20Analysis%20Results%20SAS.pdf)

## Visualizations (PowerBI, Tablueau, ScatterText)

<h2>  <a id="covid_powerBI" href="https://github.com/wandabwa2004/Visualizations/blob/master/PowerBI/Worldwide_Coronacases.pbix"> 1. PowerBI: Coronavirus numbers as at 10/03/2020</a> </h2>

[Code](https://github.com/wandabwa2004/Visualizations/blob/master/PowerBI/Worldwide_Coronacases.pbix)

* COVID-19 Numbers by 10/03/2020 in PowerBI.

![COVID-19 Numbers as at 10/03/2020](https://github.com/wandabwa2004/Visualizations/blob/master/PowerBI/coronaviz.jpg "COVID-19 Numbers as at 10/03/2020")

<h2>  <a id="scatter_tepapa" href="https://github.com/wandabwa2004/Visualizations/tree/master/Scattertext"> 2. ScatterText: Museum of  New Zealand Reviews TripAdvisor Reviews and Related Topics</a> </h2>

[Repository](https://github.com/wandabwa2004/Visualizations/tree/master/Scattertext) 

Used Scattertext package in Python to interactively visualize reviews related to the Museum of  New Zealand.

[Visualization of Terms Code](https://lnkd.in/gyvXhdH)  | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/Visualizations/blob/master/Scattertext/Tepapa_Reviews-Visualization.html)

[Visualization of Topics Code] (https://lnkd.in/gzvNBwF) | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/Visualizations/blob/master/Scattertext/Tepapa-Visualization-Empath_Topics.html)

![Terms visualizations  in ScatterText](https://github.com/wandabwa2004/Visualizations/blob/master/Scattertext/tepapa_reviews.PNG "Terms visualizations  in ScatterText")

## Model Deployment 
<h2>  <a id="deployment_political" href="https://github.com/wandabwa2004/sent_analyzer_kenya"> 1. Kenyan Political Sentiments Monitor - The Polimeter</a> </h2>

[Code](https://github.com/wandabwa2004/sent_analyzer_kenya) | [Deployed App](https://sentiment-politics-kenya.herokuapp.com/)

![Political Sentiment Analyzer](https://github.com/wandabwa2004/sent_analyzer_kenya/blob/master/sentianalyzer.PNG "Kenyan Political Sentiment Analyzer")

<h2>  <a id="ds_eng" href="#> Data  Science Foundations and Engineering Certifications</a> </h2>
 
### [Professional Certificate in Data Engineering with Google Cloud](https://www.coursera.org/account/accomplishments/professional-cert/BZ2M655H46HQ)
 * [Google Cloud Platform Big Data and Machine Learning Fundamentals](https://www.coursera.org/account/accomplishments/records/K28J2JA6M6YC)
 * [Modernizing Data Lakes and Data Warehouses with GCP](https://www.coursera.org/account/accomplishments/records/4NSV7J7NXA2D)
 * [Building Resilient Streaming Analytics Systems on GCP](https://www.coursera.org/account/accomplishments/records/8F8MW43XMFNR)
 * [Smart Analytics, Machine Learning, and AI on GCP](https://www.coursera.org/account/accomplishments/records/A7HEZXEF8QZ4)
 * [Building Batch Data Pipelines on GCP](https://www.coursera.org/account/accomplishments/records/GQA9NJRVWLJT)
 * [Preparing for the Google Cloud Professional Data Engineer Exam](https://www.coursera.org/account/accomplishments/records/6X7HCFRALZW5)

### Data  Science Foundations 
 * [Machine Learning Foundations: A Case Study Approach](https://www.coursera.org/account/accomplishments/records/PFQR5F5UCMY4) 
 * [The Data Scientist’s Toolbox](https://www.coursera.org/account/accomplishments/records/YYD6FL74G32U)
 
<h2>  <a id="publications" href ="https://scholar.google.com/citations?user=0iEgEHYAAAAJ&hl=en"> Google Scholar Profile</a> </h2>



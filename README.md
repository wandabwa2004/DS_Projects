<!-- <p align="center"><img width=43.5% src="https://github.com/yashprakash13/data-another-day/blob/main/Data%20Another%20Day.png"></p> -->
# Artificial Intelligence(AI),Generative AI  (Gen AI), Data Science, Engineering  and  Analytics Projects and Solutions 
<h4 align="center">Senior Data Scientist with extensive experience in the financial sector, specializing in developing innovative AI and data-driven solutions. My portfolio showcases a range of self-driven projects that demonstrate my passion for pushing the boundaries of technology and solving complex problems.
My work spans multiple domains:

Artificial Intelligence: Custom AI solutions leveraging deep learning and machine learning algorithms to solve complex business challenges.
Generative AI: Cutting-edge projects exploring the capabilities of large language models, text-to-image generation, and other generative technologies to create innovative applications.
Data Science: End-to-end data science solutions including predictive modeling, statistical analysis, and advanced feature engineering techniques.
Engineering: Robust data engineering pipelines and scalable architectures that support production-ready AI systems.
Analytics: In-depth analytical projects showcasing business intelligence, data visualization, and actionable insights extraction.

Each project in this portfolio represents independent work completed alongside my professional role in financial services, reflecting my commitment to continuous learning and technical excellence. These solutions demonstrate my ability to translate complex technical concepts into practical, value-driving applications. 
</h4>

<p align="center">
  <a href="https://www.python.org">
    <img src="https://img.shields.io/badge/Python-3.6%2C%203.7%2C%203.8%2C%203.9-green?style=for-the-badge"
         alt="Python versions">
  </a>
  <a href="https://github.com/wandabwa2004">
    <img src="https://img.shields.io/badge/GitHub-Profile-blue?style=for-the-badge"
         alt="GitHub">
  </a>
  <a href="https://medium.com/@hermanwandabwa">
    <img src="https://img.shields.io/badge/Medium-Blog-orange?style=for-the-badge"
         alt="Medium Data  Science  Blog">
  </a><br/>
</p>



# Table of Contents
### 1. Large Language  Models (LLMs)  and  Generative AI (Gen AI) 
* [KnowItAll: Your AI-Powered  Assistant](#llmsknowitall) 

### 2. Python 
  * [Drive Customer Success: Supercharging Safaricom’s Product FAQs with Llama 2 Model](#llama2finetuning)  
  * [Web Scraping Product-Driven Question-Answer Pairs](#webscraper)  
  * [Harnessing GPT-Powered AI to Query and Summarize Multiple Hansard Reports in the Kenyan Parliament](#gpthansard) 
  * [Uncovering Patterns and Trends in Ausgrid Power Outage Data](#ausgrid)
  * [Timeseries Modelling for Sales Data](#timeseriesales) 
  * [Olympics Data  Analytics from (1896 - 2020)](#olympicsanalytics) 
  * [Inside DP Ruto’s Social Network Engine (Part 1)](#socialnetwork1)
  * [Online Sharepoint 365  Uploader](#sharepointuploader)
  * [Financial Crime Fraud Analytics](#financialscrime)
  * [Political Content Sentiment Analyzer](#politicalsentiment)
  * [Fitbit Data Analytics during COVID-19 Lockdown in New Zealand](#fitbit)
  * [NLP: Tweeting patterns during COVID-19 Lockdown in New Zealand](#covid_tweeting)
  * [Sea Turtle Rescue Forecast Challenge](#sea_turles)
  * [Bidirectional Encoder Representations from Transformers (BERT) in computation of a few African Cities Happiness](#bert_happiness)
  * [Te Papa Tongarewa (Museum of New Zealand) Sentimental Footing](#tepapa_sentiments)
  * [We are just a Loquacious lot. 2019 Kenyan Social Beat](#loquacious)
### 3. R 
  * [Emotion Detection in New Zealander's Tweets  Over the COVID-19 Lockdown Period](#emotions)
  * [Speech Analytics: State of the Nation Addresses by Kenya's President, Uhuru Kenyatta](#speech_analytics)
### 4. SAS
  * [Black Friday Sales Analytics](#black_friday)
### 5. Visualizations (PowerBI, Tableau, ScatterText)
  * [PowerBI: Coronavirus numbers as at 10/03/2020](#covid_powerBI)
  * [ScatterText: Museum of  New Zealand Reviews TripAdvisor Reviews and Related Topics](#scatter_tepapa)
### 6. Model Deployment 
  * [Kenyan Political Sentiments Monitor - The Polimeter](#deployment_political)
### 7. [Data  Science and Engineering  Certifications](#ds_eng)
### 8. [Publications](#publications) 

# Projects
## Large Language  Models (LLMs)  and  Generative AI (Gen AI) 
<h2>  <a id="llmsknowitall" href="https://github.com/wandabwa2004/llmchatbot"> KnowItAll: Your AI-Powered  Assistant </a> </h2>

KnowItAll: Your AI-Powered  Assistant

[Link to the repo and code:](https://github.com/wandabwa2004/llmchatbot) 

I detail how I developed a multi-functional chatbot named KnowItAll, powered by OpenAI’s GPT-4 API, to handle diverse tasks such as answering questions, generating content, translating text, and writing code. While GPT-4 inherently possesses the ability to generate responses based on contextual understanding, this alone does not make it an intuitive assistant for specific use cases. To address this, KnowItAll leverages carefully crafted system and feature-specific prompts to align the AI's responses more closely with user expectations. By tailoring the input prompts to predefined user needs—such as content generation or code writing—the chatbot effectively serves as a highly capable and adaptive virtual assistant. This approach ensures that the chatbot not only understands explicit instructions but also delivers responses optimized for each feature, enhancing user interaction and satisfaction.

## Python
<h2><a id="llama2finetuning" href="https://hermanwandabwa.medium.com/finetuning-llama-2-model-on-safaricoms-product-related-faqs-c9b226a43106"> Drive Customer Success: Supercharging Safaricom’s Product FAQs with Llama 2 Model </a> </h2>

Transforming Customer Experiences: How a Finetuned Llama 2 Model Can Empower Product FAQs:

[Link to Article:](https://hermanwandabwa.medium.com/finetuning-llama-2-model-on-safaricoms-product-related-faqs-c9b226a43106) with all code 

I detail how I finetuned an open-source Llama 2 model with Safaricom’s product and service-related FAQ question and answer pairs. Models such as Llama 2 possess the capability to predict the subsequent token within a sequence. However, this predictive ability alone does not render them highly effective virtual assistants, as they do not inherently respond to explicit instructions. To bridge this gap, a technique known as instruction tuning is applied to align their responses more closely with human expectations. I made use of Supervised Fine-Tuning (SFT) with the FAQ pairs. In this approach, models are subjected to training on a dataset consisting of paired instructions and corresponding responses, as in our case with the Question-Answer pairs. The goal is to optimize the internal model parameters within the LLM to minimize the disparity between the generated answers and the ground-truth responses, which serve as reference labels.


<h2><a id="webscraper" href="https://hermanwandabwa.medium.com/web-scraping-product-driven-question-answer-pairs-214988cdfed4"> Web Scraping Product-Driven Question-Answer Pairs </a> </h2>

[Link to Article:](https://hermanwandabwa.medium.com/web-scraping-product-driven-question-answer-pairs-214988cdfed4) with all code 

This is part one of a two-part series where I build a scraper to get most FAQs about Safaricom products to use later on in fine-tuning an open-source Llama 2 Large Language Model on the data and eventually developing a chatbot that users could interact with the fine-tuned model.

I used the following Python packages: 

1. BeautifulSoup: to parse HTML and XML documents, making it easier to extract information from web pages.
2. Selenium: to automate interactions with the website. It’s particularly useful for scraping dynamic content and interacting with JavaScript-driven pages.
3. Pandas: to manipulate and store the data.
4. Random: to add random delays between requests to avoid overloading the server.

I was able  to scrape  and store  1759 non-null product-related FAQs and their answers here https://www.safaricom.co.ke/media-center-landing/frequently-asked-questions

   
<h2>  <a id="gpthansard" href="https://github.com/wandabwa2004/GPTHansard"> Harnessing GPT-Powered AI to Query and Summarize Multiple Hansard Reports in the Kenyan Parliament</a> </h2>

[Link to Article:](https://hermanwandabwa.medium.com/gpt-powered-insights-unleashing-the-867084d0e4f9) with all code 

The Hansard and Audio Services Directorate within the Kenyan Parliament is responsible for recording and producing verbatim reports of parliamentary proceedings and committee deliberations. With a curiosity to understand the topics discussed by members of parliament over time, I sought to explore the Hansard reports for specific sessions or sittings. However, due to the length of these reports and the challenge of identifying relevant dates, this endeavor proved to be time-consuming and potentially unproductive.

This led me to explore effective methods of querying PDF documents and obtaining insightful information on specific topics. After considering various options, I decided to leverage Large Language Models (LLMs), with OpenAI being my preferred choice.

The  analysis  follows the below : -

1. Sourcing data: Extracting PDFs from the official website, as they are publicly available.
2. PDFs Validity Check
3. Setting up dependencies: Configuring the necessary software libraries and tools.
4. Querying the Hansard reports for 2018: Although there is no particular significance attributed to the 2018 reports, I chose this subset for demonstration purposes.
5. Summarizing PDFs

<h2>  <a id="ausgrid" href="https://github.com/wandabwa2004/Data-Analysis/tree/main/Ausgrid%20Outages"> Uncovering Patterns and Trends in Ausgrid Power Outage Data]</a> </h2>

[Link to Notebook](https://github.com/wandabwa2004/Data-Analysis/blob/main/Ausgrid%20Outages/Historical_Data_Analysis.ipynb) <br>
[Link to Article](https://hermanwandabwa.medium.com/uncovering-patterns-and-trends-in-ausgrid-power-outage-data-ec538d4f70f9)

Power outages are a prevalent challenge encountered by utility companies, highlighting the need for a thorough analysis of historical data to understand patterns and trends. I analysed the historical outage data for Ausgrid, Australia’s largest electricity distributor, which services 1.7 million customers across Sydney, the Hunter Valley, and the Central Coast.


In summary:

1. The analysis shows that equipment faults have consistently been a major reason for power outages in the Ausgrid network.
2. The year 2020 recorded the highest number of outages during the period covered by the dataset.
3. Based on the data, Gosford, Hornsby, and Wyong were the locations most affected by power outages. Gosford’s cause of outages is mostly environmental-related factors.
4. Power outages were found to be more prevalent in the afternoons, with a peak at around 6 PM across all days of the week. As such, Ausgrid’s rostering for the afternoon shift should consider having more workers on standby. Mornings and late evenings are usually quieter periods in terms of power outages.
5. The analysis indicates that power outages are more prevalent on Saturdays. Therefore, there is a need for better workforce planning on this day.


<h2>  <a id="timeseriesales" href="https://github.com/wandabwa2004/Timeseries-Modelling"> Sales Data  Timeseries Modelling</a> </h2>

[Link to Notebook](https://github.com/wandabwa2004/TimeseriesModelling/blob/master/Data%20Science%20Assessment%20-%20Sales%20Records%20Predictions.ipynb)

This is a prediction problem based on a time-series dataset of online sales of a UK-based store. The company sells unique all-occasion giftware. Wholesalers make up a high number of their customers. The sales data is from 01/12/2009 to 09/12/2011. The problem here is to predict the sales for the next 22 days based on this historical data as the owner is interested in knowing the expected revenue at this time to be sure of the sports car he buys his partner for Christmas.

**Dataset**
Dataset has 1067371 sales records. Each record is identified by 8 attributes i.e. Invoice, StockCode, Description, Quantity, InvoiceDate, Price, Customer ID and Country . Individual descriptions are found here https://www.kaggle.com/mashlyn/online-retail-ii-uci#

Dataset name: online_retail_II.csv and can be found here https://www.kaggle.com/mashlyn/online-retail-ii-uci. I could not directly upload it here due to the 25MB size limitation.

**What the Notebook Covers:**
1. Ingesting the dataset
2. Perform Exploratory Data Analysis (EDA). This includes operations related to: -
a) Total daily, weekly, and monthly sales volumes.
b) Last months’ revenue share by product and by customer.
c) Weighted average monthly sale price by volume
3. Data Cleaning and Encoding
4. Data Modelling (Using Facebook's Prophet)in relation to time series-based revenue prediction.

![Sales Data  Timeseries Modelling](https://github.com/wandabwa2004/Timeseries-Modelling/blob/master/timeseries.png "Time Series  Modelling")

<h2>  <a id="olympicsanalytics" href="https://github.com/wandabwa2004/OlympicsAnalytics"> Olympics Data  Analytics from (1896 - 2020) </a> </h2>

[Link to Notebook](https://github.com/wandabwa2004/OlympicsAnalytics/blob/main/Olympic%20Medals%20Over%20Time.ipynb)

EDA and analytics on a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Tokyo in 2020. The data was scraped from www.sports-reference.com.

**Objective:**
To visualize how Olympics has evolved over time with special emphasis on African countries that began participating quite many years after the competitions began. This is achieved by merging and visualizing output from the above datasets.

![Olympics Data  Analytics](https://github.com/wandabwa2004/OlympicsAnalytics/blob/main/AfricanMedals.gif "African Countries Medal Tally")

<h2>  <a id="socialnetwork1" href="https://hermanwandabwa.medium.com/inside-dp-rutos-social-network-engine-part-1-634851d02bfa?sk=f5826ac72d7ca6f8661f9e3148c3fd81"> Inside  DP Rutos Social Network </a> </h2>

[Link](https://hermanwandabwa.medium.com/inside-dp-rutos-social-network-engine-part-1-634851d02bfa?sk=f5826ac72d7ca6f8661f9e3148c3fd81)

Social network mining for  users within Kenya's Deputy President's Twitter account. Three significant weaknesses are in this network setup: -

* Isolated users — Isolates in the network, more so around @WilliamSRuto’s cluster are many. This means that they are likely to miss out what for example @MbuiMumbi or @oleitumbi disseminates, unless is re-shared or by @WilliamSRuto which may not always be the case. This is depicted by the low Reciprocated Vertex Pair Ratio.
* Weak inter and intra cluster edges — Connections between clusters are weak, less for G1 to G5. This means content in the clusters is less likely to reach all users in it. The situation is even worse for inter-cluster connections.
* Influence isolation — @oleitumbi is the only user of influence in this collection period. The user is a prime target for account suspension e.g. if someone reports of any policy violations. This is depicted by the low graph density value.

![DP Ruto's  Twitter Social Network Engine](https://github.com/wandabwa2004/SocialNetworkMining/blob/main/rutonetwork.png "Social Influence  Network Map")

<h2>  <a id="sharepointuploader" href="https://github.com/wandabwa2004/SharepointUploader"> Sharepoint 365 Uploader </a> </h2>

[Repository](https://github.com/wandabwa2004/SharepointUploader)

Tool designed and developed using Python and Streamlit to help you upload files to an online Sharepoint location. This works with Sharepoint 365 but can be modified to fit earlier SharePoint versions. Current functionality includes:

* Specifying the folder path to the files to be  uploaded (Source URL).
* Summary information of the files to be  uploaded. 
* Specification of Sharepoint login and related upload details. 
* Creation of  a folder based on the todays date format in the base URL that is user specified.
* Upload of the files matching  the  specified extension (currently .xlsx) to the  new folder in the base URL. File format can be changed

![Sharepoint Uploader](https://github.com/wandabwa2004/SharepointUploader/blob/main/sharepoint.png "Correlation of factors in financial crime")
## Notes on Usage
* A deployed version of  the app can be found here https://sharepointuploader.herokuapp.com/. The app can also be cloned and run locally using streamlit: `streamlit run SharepointUploader.py`. When doing this, ensure you have the required modules listed in the requirements file.
* Make sure  the account  details for  accessing  Sharepoint on your  domain are valid. Normally, the username  is your domain specific email and password. 

## Bugs, Enhancements and Comments
All comments, bug reports and enhancement requests are welcome. To do so, please submit a new issue and I will work hard on improving the app. 

## Future Functionality
Future functionality will likely include:
* Option to specify file formats  to be uploaded in a folder with mixed file types. 
* Email trigger to the  username once  the files are all uploaded. 

<h2>  <a id="financialscrime" href="https://github.com/wandabwa2004/Fraud_Analytics"> Financial Crime Fraud Analytics </a> </h2>

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

<h2>  <a id="politicalsentiment" href="https://github.com/wandabwa2004/sent_analyzer_kenya"> Political Content Sentiment Analyzer </a> </h2>

In this  project, I setup a tweets  collection framework for tweets belonging to five politicians in Kenya. I analyzed the tweet sentiments/emotions over time, packaged the same in a Streamlit App and hosted the same on Heroku. 

[Code](https://github.com/wandabwa2004/sent_analyzer_kenya) | [Deployed App](https://sentiment-politics-kenya.herokuapp.com/)

<h2>  <a id="fitbit" href="https://github.com/wandabwa2004/Fitbit-Analytics-Lockdown/"> Fitbit Data Analytics during  COVID-19 Lockdown in New Zealand </a> </h2>

[Repository](https://github.com/wandabwa2004/Fitbit-Analytics-Lockdown/) | [Notebook](https://github.com/wandabwa2004/Fitbit-Analytics-Lockdown/blob/master/Fitbit%20Analytics%20-%20Lockdown.ipynb) | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/Fitbit-Analytics-Lockdown/blob/master/Fitbit%20Analytics%20-%20Lockdown.ipynb) | [Blog Article](https://medium.com/swlh/6-kgs-lost-in-31-days-of-covid-19-lockdown-a-data-analytics-perspective-a0061e0689f2?source=friends_link&sk=7c19969f1c54fb013d3cdae45319d78d)
* Analytics of my body, activity and sleep data during the COVID-19 lockdown. 
* Identification of important factors that necessitated weight loss during the lockdown time. 
![Fitbit Data Analytics](https://github.com/wandabwa2004/Fitbit-Analytics-Lockdown/blob/master/fitbit.png "Fitbit Data Analytics")

<h2>  <a id="covid_tweeting" href="https://github.com/wandabwa2004/COVID-19-Lockdown"> NLP: Tweeting patterns during  COVID-19 Lockdown in New Zealand </a> </h2>

[Repository](https://github.com/wandabwa2004/COVID-19-Lockdown) | [Notebook](https://github.com/wandabwa2004/COVID-19-Lockdown/blob/master/COVID-19%20Lockdown%20Tweeting.ipynb) | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/COVID-19-Lockdown/blob/master/COVID-19%20Lockdown%20Tweeting.ipynb)
* Collection of streaming tweets from Auckland and Wellington, New Zealand's largest cities during  COVID-19 Lockdown period. 
* Descriptive analytics on the tweeting patterns by users from the  two cities. Aucklanders seemed to work more than tweet. 
* Topics of discussion were  semantically identical across the cities. Visualized by PyLDAVis.

![Tweeting  Patterns during  COVID-19 Lockdown](https://github.com/wandabwa2004/COVID-19-Lockdown/blob/master/tweeting%20_covid.png "COVID-19 Tweeting Patterns  in NZ")

<h2>  <a id="sea_turles" href="https://github.com/wandabwa2004/sea-turtle-forecast-challenge"> Sea Turtle Rescue Forecast Challenge </a> </h2>

[Repository](https://github.com/wandabwa2004/sea-turtle-forecast-challenge) | [Notebook](https://github.com/wandabwa2004/sea-turtle-forecast-challenge/blob/master/Sea%20Turtle%20Rescue%20Forecast%20Challenge.ipynb) | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/sea-turtle-forecast-challenge/blob/master/Sea%20Turtle%20Rescue%20Forecast%20Challenge.ipynb)

The objective of the competition was to create a machine learning model to help Kenyan non-profit organization Local Ocean Conservation anticipate the number of turtles they will rescue from each of their rescue sites as part of their By-Catch Release Programme https://zindi.africa/competitions/sea-turtle-rescue-forecast-challenge.
* Descriptive analytics and  EDA for the dataset. Included encoding etc for better modelling. 
* 1.1897261428182493 RMSE as the measurement metric. 

![Turtles Capture and  Release Programme](https://github.com/wandabwa2004/sea-turtle-forecast-challenge/blob/master/turtles.png "Captured Numbers/Year")

<h2>  <a id="bert_happiness" href="https://github.com/wandabwa2004/BERT_Happiness_Index"> Bidirectional Encoder Representations from Transformers (BERT) in computation of a few African Cities Happiness </a> </h2>

[Repository](https://github.com/wandabwa2004/BERT_Happiness_Index) | [Notebook](https://github.com/wandabwa2004/BERT_Happiness_Index/blob/master/BERT-%20Happiness2.ipynb) | [nbviewer](https://nbviewer.jupyter.org/github/wandabwa2004/BERT_Happiness_Index/blob/master/BERT-%20Happiness2.ipynb) | [Blog Article](https://towardsdatascience.com/kigali-the-2019-happiness-capital-a0085dc1efc4?source=friends_link&sk=4ea0299439406d885c6c4d758f630643)
* Collection of  tweets from the different cities via geocoding. 
* Translation via  GoogleTranslate Python library for modelling.
* Descriptive analytics of the datasets per country. 
* Modelling  via  BERT and batch sentiment prediction per tweet and grouped by cities. 
* The highest probability to a sentiment was assumed to be the true sentiment of the  tweet. 

![BERT Happiness Index](https://github.com/wandabwa2004/BERT_Happiness_Index/blob/master/berthappiness.PNG "BERT Happiness Index for a few African Cities")

<h2>  <a id="tepapa_sentiments" href="https://towardsdatascience.com/te-papa-tongarewa-museum-of-new-zealand-sentimental-footing-d062e41e430f?source=friends_link&sk=2f0c07b247153effb1639d5193a898d3"> Te Papa Tongarewa (Museum of New Zealand) Sentimental Footing</a> </h2>

[Article](https://towardsdatascience.com/te-papa-tongarewa-museum-of-new-zealand-sentimental-footing-d062e41e430f?source=friends_link&sk=2f0c07b247153effb1639d5193a898d3)

Code Snippets with:-
* Descriptive Analytics of  Trip Advisor reviews for Museum of New Zealand (Te Papa Tongarewa)
* Sentiment  Analysis of the reviews.

![Sentiment Over Time](https://miro.medium.com/max/700/1*neOrnIcTZEMh5KW0f6jupA.png "Te Papas Sentiments over Time")

<h2>  <a id="loquacious" href="https://medium.com/@hermanwandabwa/we-are-just-a-loquacious-lot-2019-kenyan-social-beat-458938d5a066?source=friends_link&sk=a8d224ee3022decff6b78a4b5f9f8846"> We are just a Loquacious lot. 2019 Kenyan Social Beat </a> </h2>

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

## Visualizations (PowerBI, Tableau, ScatterText)

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



# Data Science and  Analytics Projects
This portfolio consists of several data science and anaytics projects illustrating the work I have done in order to further develop my data science skills.
# Table of Contents



# Projects
## 1. Financial Crime Fraud Analytics
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

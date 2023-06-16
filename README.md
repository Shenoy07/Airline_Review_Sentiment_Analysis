# Airline_Review_Sentiment_Analysis

Sentiment analysis or opinion mining refers to the use of natural language processing (NLP), text analysis and computational linguistics to identify and extract subjective information from the source materials. 
In our project, we used consumer comments regarding airline services using Twitters. Tweets are one of the most important sources of opinion mining data since they include a big number of tweets that must be processed & evaluated to make a choice or improve a certain service.  

This dataset categorizes Twitter tweets into positive and negative categories, which was tested and validated. We tested our model on a dataset that included tweets from six different airlines in the United States. For this, the data is taken from Kaggle and labelled as a positive and negative category before pre-processing it. Pre-processing of the dataset was carried out as part of the data transformation stage.  

We started our model by pre-processing steps, tokenized text, removed stopwords, Parts of Speech tagging, Lematization. Next we used a set of criteria, we cleaned tweets as well as used them as training data for statistical models. This is similar to how knowledge-based expert systems are commonly used as training data.  

To transform the text data into numerical values or vectors to represent them as feature vectors, we used the CountVectorizer and TF-IDF models, which we developed later.  

We divided our data into two groups: 80 percent for training, and 20 percent for testing. The next phase is fitting the data into several machine learning models, which are described below. There are many alternatives for NLP, we use Naïve and SVM. 

Finally, we tested and validated the model on the test dataset for analysing the feedback about US airlines. We get an integer sentiment value for each model. This will help airline companies to understand customer needs and which sector (such as service, food, staff etc.) needs improvement. 

 
 

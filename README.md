# Hotel Price Prediction and Recommendation Content Based with Clustering and Context Analysis using Airbnb Singapore Data

## Background
I chose this topic for my final project because I want to increase the customer's experience while using our application. 
frequently, customers are confuse when they need to choose a hotel for stay. With recommender system, application owner can help consumers
by offer the similar products to the customer so they have more option and can increase the chance of customer to get the suitable products.
as a result, they will satisfied with our company's performance and will back to us again. 

Furthermore, while customers are searching the properties for themself, sometimes difficult for them to measure how worth the value of this 
property. Using the price prediction, I want to help customer to measure the normal price for each property. If the property
has a huge difference between prediction and real price, customer can do deeper research about the property, because maybe the property 
is have fancy amenities, etc, which cause the price become more expensive.

## Workflow
Firstly, I using three source to get the insight from data and machine learning part, which are listings.csv, listings2.csv and calender2.
I do this first step at 'Data Preparation+EDA.ipnyb'. For the sentiment analysis and clustering, I use different notebook. For the 
sentiment analysis, I work on 'sentiment analysis.ipnyb' and export a csv with title 'sentiment' while for clustering I work on 
'unsupervised clustering.ipnyb' and export a csv with title 'labeling'. These two csv is imported to main notebook, 'Preparation+EDA.ipnyb' for
further analysis and combination. After done some data cleaning, I export a csv with title 'price_clean.csv' from this notebook
which will be used for price prediction part in 'price_prediction.ipnyb'. Finally, for the last part, which is recommendation system, I
work on 'recommendation content based + cluster.ipynb'.

After all of the analysis is done, I make a dashboard using dash plotly, which you can see in 'dashboard.rar'. The deployment still on
progress.

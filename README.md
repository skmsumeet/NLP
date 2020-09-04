Social media analytics using LDA

This file contains the basic information about how I performed LatentDirichletAllocation for Topic modelling on a given data set of mixed customer tweets. This can prove beneficial for impriving cutomer support and derive if customers are satisfied or not. furthermore performing sentiment analysis can help the organisations to understand customer emotion and act accordingly. A happy customer can be pitched in ideas of more product sale or upselling of existing products. 

I used sample.csv as the training data set. downloaded it from git- https://www.kaggle.com/thoughtvector/customer-support-on-twitter/download 
Cleaned the column ‘text’ using re
Then used count vectorizer class from the sklearn.feature_extraction.text module to create a document term matrix
Following that applied LDA to the document term matrix.
It divided the column text into 4 topics each containing the words are mostly related to that segment
Post that sentiment analysis can be performed on particular topic set to find out the reviews and hence actionable insights can be drawn out using the former.


 

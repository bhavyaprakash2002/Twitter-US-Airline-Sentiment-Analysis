# Twitter-US-Airline-Sentiment-Analysis

The repo focuses on using Natural Language Processing (NLP) to classify the sentiment of US airlines commands. 
The data has been pre-processed, features are extracted and ensembling methods have been applied to classify the sentiments or to do the sentiment analysis.
Pre-processing steps involved:
 1. Removing stop-words from the text.
 2. Ruling out the punctuations.
 3. Lemmatizing the words by WordNetLemmatizer.

Important libraries that were used are:
 1. NLTK
 2. SpaCy
 3. Pandas

Feature extraction was done and the text was converted into vectors by CountVectorizer (CV).
Random Forest ensembling methods was used and training and testing scores of 0.99 and 0.75 was obtained.

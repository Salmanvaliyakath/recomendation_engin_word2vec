# recomendation_engin_word2vec
This repo describes a Recommendation engine implementation for a store keeper to enhance its business by recommending right product to the costumers.


### Indroduction
For any recomendation engine implementation we require a huge data, Also we have to convert these text data in to machine understanding format, Embedding. Here I am using a popular Embedding technique Word2Vec. The Word2Vec Embeddding can be used for the Vector representation of the words.


Using the purchase data from a retail store. We are training the Word2Vec model here with the data we have, 

Load and preprocess the data, split the data to train and test data, prepare the data to train the word2vec model.

Create a dictionary of StockID and Description.

Create a customer purchase history (StockID's) data and train the word2vec model.

The model is trained and ready to predict the similar vector for a input StockID.

Translate the Predicted StockID with Dictionary.


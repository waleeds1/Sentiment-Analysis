
# Sentiment-Analysis
Sentiment analysis of reviews using CNN and RNN models. Performed while taking the [Intro to TensorFlow for Deep Learning](https://www.udacity.com/course/intro-to-tensorflow-for-deep-learning--ud187) course from udemy. Each word was broken into subwords so that the model can perform better, words containing *"dis-"* or *"-less"* are usually negative words. This would help the model make predictions on unseen words more accurately by analysing the subwords. Sentiment analysis was performed on 2 differnet dataset. 
## Small Dataset
The First one was on reviews are from amazon and yelp, the dataset can be found on [kaggle](https://www.kaggle.com/datasets/marklvl/sentiment-labelled-sentences-data-set). Bidirectional LSTM was used for this model. We compared the performance between a simple neural network with embeddings and dense layers, against bidirectional LSTM. LSTM predicted with more confidence the sentiment of the reviews.
## Large Dataset
The [SST](https://nlp.stanford.edu/sentiment/index.html) dataset from [GLUE benchmark](https://gluebenchmark.com/) was used. Multiple models were used and compared performance with. CNN and RNNs such as Bidirectional GRU and LSTM were used.

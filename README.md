# sentiment-analysis-on-movie-review-dataset
The dataset is got from rotten tomatoes. Here the movie reviews were classified into 5 categories as positive, somewhat positive, neutral, negative, and somewhat negative. First the data is per-processed using NLTK. The embedding matrix is based on GloVe model. Using Tensorflow an Ids matrix was created which was then fed into LSTM cells for classification. The accuracy is nearly 70%

Ref:
1.https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews/discussion/26446
2.https://www.oreilly.com/learning/perform-sentiment-analysis-with-lstms-using-tensorflow
3.https://www.kaggle.com/meenaj/movie-reviews

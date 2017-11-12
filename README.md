# sentiment-analysis-on-movie-review-dataset
Here the movie reviews were classified into 5 categories as positive, somewhat positive, neutral, negative, and somewhat negative. The dataset was got from rotten tomatoes. First the data was pre-processed using eautifulSoups, Re and NLTK. The word vector matrix is based on GloVe model created by Stanford. Using Tensorflow, the wordVec for each word was fed into LSTM cells for classification. The accuracy is nearly 70%

Ref:

1.https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews/discussion/26446
2.https://www.oreilly.com/learning/perform-sentiment-analysis-with-lstms-using-tensorflow
3.https://www.kaggle.com/meenaj/movie-reviews

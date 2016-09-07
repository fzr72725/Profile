# Profile
This repository contains some machine learning projects that I have been worked on recently.
# Description
1. [Digit Recognizer] (https://www.kaggle.com/c/digit-recognizer)
 * The training and testing data files are downloaded from Kaggle.com to the "data" folder in this repository.
    * [training data] (https://github.com/fzr72725/Profile/blob/master/data/train_MNIST.csv)
    * [testing data] (https://github.com/fzr72725/Profile/blob/master/data/test_MNIST.csv)
 * There are two ipython notebooks containing different algorithms for the prediction.
    * [MNIST_knn.ipynb] (https://github.com/fzr72725/Profile/blob/master/MNIST_knn.ipynb)
      This was the first one I wrote. It uses sklear.knn to predict the classes. The accuracy is around 97%, it got me a ranking of 475 out of 1200 on Kaggle's leaderboard.
    * [MNIST_tensorflow.ipynb] (https://github.com/fzr72725/Profile/blob/master/MNIST_tensorflow.ipynb)
      In this notebook I used Google's Tensorflow to apply convolutional neurual network on the data. The accuracy improved by 1%. My ranking
      jumped to 192 on the leaderboard.
2. [Bike Sharing Demand] (https://www.kaggle.com/c/bike-sharing-demand)
 * The training and testing data files are downloaded from Kaggle.com to the "data" folder in this repository.
    * [training data] (https://github.com/fzr72725/Profile/blob/master/data/train.csv)
    * [testing data] (https://github.com/fzr72725/Profile/blob/master/data/test.csv)
 * [bikeShare.ipynb] (https://github.com/fzr72725/Profile/blob/master/bikeShare.ipynb)
    * For this prediction, I used various algorithms from sklearn.linear_model on the continuous features, as well as decision tree regressor on categorical features. Also, I clustered the data into two groups based on different patterns corresponding to weekday or weekend. Furthur
  modeling can be done to see if by clustering the data, the prediction accuracy can be improved.
3. Yelp Review NLP
 * The training and testing data files are downloaded from a tutorial github repo into the "data" folder in this repository.
    * [raw data] (https://github.com/fzr72725/Profile/blob/master/data/yelp.json)
 * [NLP_NaiveBayes.ipynb] (https://github.com/fzr72725/Profile/blob/master/NLP_NaiveBayes.ipynb)
    * In this notebook, I applied various text processing method onto the collected yelp review text content. After preprocessing, I ran Naive Bayes on the data for the prediction.
4. [Expedia Hotel Recommendations] (https://www.kaggle.com/c/expedia-hotel-recommendations)
 * he training and testing data files are too large to be stored at Github. 
 * This is still in progress.

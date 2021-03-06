# Predicting Boston Housing Price

The goal of this project is to build a regression model that outputs a single price value (median value of owner-occupied homes per $1000).

Dataset obtained from [Kaggle](https://www.kaggle.com/prasadperera/the-boston-housing-dataset/data?select=housing.csv) or [Keras sample datasets](https://storage.googleapis.com/tensorflow/tf-keras-datasets/boston_housing.npz) 


## Results
The dynamics of the loss function (mse) are as folowing:

<p align="center">
  <img src="https://github.com/luis-a-miranda/AI-Boston-Housing-Price/blob/main/train_val_error.png">
 </p>

When implementing the model on the test dataset, the model's score is RMSE = 3.848. 

This result corresponds to a 19th position on the [Kaggle leaderboard](https://www.kaggle.com/c/boston-housing/leaderboard).

<p align="center">
  <img src="https://github.com/luis-a-miranda/AI-Boston-Housing-Price/blob/main/kaggle_leaderboard.PNG" width="500" height="300">
 </p>

## Acknowledgements
This project is based on the content from the [MIT Deep Learning](https://deeplearning.mit.edu) course.

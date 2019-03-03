# predictAirBnBPrice

https://www.kaggle.com/rudymizrahi/airbnb-listings-in-major-us-cities-deloitte-ml/home?fbclid=IwAR2Ge85GYUGjAOtLfs0su-G5KwS9Htx769nF-X6kKF0I-CciqwiQFAnLs3A


Introduction The aim of this competition was to predict the price of AirBnB listings in major U.S. cities.

​Instructions 1. Using the software of our choice, they asked us to build a model with the training data (train.csv) that predicts the variable "log_price"

Then we needed to run the model on the test dataset (test.csv) to generate predictions in the format found in the sample submission (sample_submission.csv)
Evaluation The evaluation metric for the competition was the Root Mean Squared Error (RMSE) score.

Data The training data for the competition consist of the following columns:

id : Record identifier
log_price : log(price) [The logarithm used is natural log]
..... : 25 features for the listing
There are five files provided for this competition:

train.csv . : Training data
test.csv . : Test data
sample_submission.csv : Sample submission file
sample_script.py : Sample python model
sample_script.R : Sample R model
Submission

The submission file for the competition should consist of two columns:

id : Record identifier for the test observation
log_price : Prediction for the log(price) of the listing
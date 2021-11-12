# Project2
This repository is about building a model for solving the classification problem using the given auto dataset.

## Requirements
- TensorFlow 2.x.x
- Tensorflow.keras
- Scikit-learn
- Numpy
- Pandas

Cloning the repository:

    git clone https://github.com/Stark-2020/Project2

## Dataset used

https://drive.google.com/drive/folders/1vy3Ytp_bus9Pg3xuZzs7SjWaIMLHXJ4-

we need to preprocess this data before using it as input for training for which we can use the prepreocessingData notebook 
present along with the main model implemetaion notebook.

This will replace the missing values with meaninful information,normalize few features and encode the non numerical data, generating new .csv files.

## Training
We have created a two layer sequential neural network which uses the categorical cross entropy loss function, for training we split the 
processed dataset using train test split function and fit the model using earlystopping.
There are two models, one without regularizer and the other one with L1 regularizer.

## Testing

testing data point was provided in the gform. You can use any test data point, changing the values in variable test.

**Output:**

For the given test point, the model predicts risk rating to be equal to zero.

    

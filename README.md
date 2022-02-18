# -Network-Intrusion-Detection
    
Kaggle competition for building a machine learning model that detects malicious traffic on a network by training it with a dataset.
  
  -First loading the needed libraries.
  
  -Loading the data by using pandas library and set the features to X and the class col to Y.
 
 -There are 3 features which are strings to we need to convert them to integer.
 
 -Then we ussed a feature selection algorithm to select the best features to work with, then we dropped the unused features.
 
 -I used Decision tree as detection model and used Grid search to get the best hyperparameters, then set it to the model.
 
 -Then use the model to predict the class of the test data and save the results on a csv file to push it to Kaggle.


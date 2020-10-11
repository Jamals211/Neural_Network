# Neural_Network
Mod 19

# Challenge Questions:

## How many neurons and layers did you select for your neural network model?
* I tried multiple hidden layers and neurons to reduce the loss mechanism and increase the accuracy of the model. <p>
* No matter how many layers and neurons were added the accuracy did not increase past 74.20%. <p>
* The most optimal model has three hidden layers with the number of neurons at 20, 16, and 8 for the three layers. <p>

## Were you able to achieve the target model performance?
* I was not able to acheive the target. <p>
* No matter what was tried, I could not get past 74.20% accuracy. <p>
  
## What steps did you take to try and increase model performance?
* The first thing I tried was adding hidden layers. After I added up to 10 hidden layers and did not see an increase in accuracy, I decided to reduce the hidden layers down to three to reduce overfitting. <p>
* I added more neurons and kept adding neurons but did not see an increase in accuracy. <p>
* I increased the number of epochs to over 1000 but did not see an increase in accuracy. <p>
* I finally changed the activation mode for each of the hidden layers but did not see an increase in accuracy. <p>
  
## What other model would you implement to solve this problem?
* The binary classificaiton model for the basic neural network did not produce a higher accuracy score. <p>
* A linear model would not work here, a support vector machine model seperates points by distance which is unlikely to work, and a random forest model works like a decision tree could work here.
  
  
# Objectives:
Import, analyze, clean, and preprocess a “real-world” classification dataset.<p>
Select, design, and train a binary classification model of your choosing.<p>
Optimize model training and input data to achieve desired model performance.<p>
  

## Import and characterize the input data.

What variable(s) are considered the target for your model? <p>
  IS_SUCCESSFUL <p>
What variable(s) are considered to be the features for your model? <p>
  The rest of the variables are the features. <p>
What variable(s) are neither and should be removed from the input data? <p>
  EIN, NAME, STATUS, SPECIAL_CONSIDERATIONS were removed <p>

## Using the methods described in this module, preprocess all numerical and categorical variables, as needed:
Combine rare categorical values via bucketing. <p>
Encode categorical variables using one-hot encoding. <p>
Standardize numerical variables using Scikit-Learn’s StandardScaler class.<p>

## Using a TensorFlow neural network design of your choice, create a binary classification model that can predict if an Alphabet Soup funded organization will be successful based on the features in the dataset.
You may choose to use a neural network or deep learning model. <p>
  I chose a binary classificaiton neural network <p>
 
## Compile, train, and evaluate your binary classification model. Be sure that your notebook produces the following outputs:
Final model loss metric <p>
  0.5550 <p>
Final model predictive accuracy <p>
  72% <p>
  















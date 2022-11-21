# Neural_Network_Charity_Analysis

## Overview of the analysis:

The goal of the analysis is to use machine learning and neural networks to predict sucessful investments. The features in the provided dataset are used to create a binary classifier that is capable of predicting whether applicants will be successful if funded. Using TensorFlow, the model will be optimized to achieve a target predictive accuracy higher than 75%.

The provided data set contains more than 34,000 organizations that have received funding. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

## Results:

First, using Pandas and the Scikit-Learn’s StandardScaler(), the dataset was preprocessed in order to compile, train, and evaluate the neural network model later on. Next, using TensorFlow, a neural network, or deep learning model, was designed to create a binary classification model that can predict if an organization will be successful based on the features in the dataset. Then the binary classification model was compiled, trained, and evaluated on it's loss and accuracy. Last, updates to the model's neurons, layers, activation fuctions, and epochs were adjusted in attempt to achieve the target model performance.

Data Preprocessing
- What variable(s) are considered the target(s) for your model?
- What variable(s) are considered to be the features for your model?
- What variable(s) are neither targets nor features, and should be removed from the input data?
- Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
- Were you able to achieve the target model performance?
- What steps did you take to try and increase model performance?

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

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

Data Preprocessing:
- The IS_SUCCESSFUL variable was identified as the target varible for the model. This variable determines whether investments were successful.
- The non beneficial identifier columns, ID and NAME, were dropped to clean up the dataset. The features for the model included all other variables (not including the target variable IS_SUCCESSFUL).
- For categorical variables with more than 10 unique values, a cutoff point was determined and values were binned to clean up the data. Categorical variables were also one-hot encoded.
-  For the neural network model 8 neurons, 5 layers, and the relu activation function was selected. ReLU is the most common and simplest activation function, so it was chosen as a starting point. 8 neurons and 5 layers were chosen as a starting point for the model by following the rule of thumb that a basic neural network is to have two to three times the amount of neurons in the hidden layer as the number of inputs.

Preliminary Results:
The first attempt did not achieve the target model performance of 75%.

<img width="809" alt="Screen Shot 2022-11-20 at 5 50 34 PM" src="https://user-images.githubusercontent.com/106785377/203592652-0e962dd6-4471-407c-bc49-08b26f11269c.png">

<img width="539" alt="Screen Shot 2022-11-20 at 5 50 47 PM" src="https://user-images.githubusercontent.com/106785377/203592677-cbb470fa-cfd9-48ec-a12a-b3a81a4342f9.png">

<img width="612" alt="Screen Shot 2022-11-20 at 5 50 57 PM" src="https://user-images.githubusercontent.com/106785377/203592687-2306f5ed-ca86-45a7-86b6-57ae45b371d6.png">


First Optimization Attempt:
- What steps did you take to try and increase model performance?

Second Optimization  Attempt:
- What steps did you take to try and increase model performance?

Third Optimization  Attempt:
- What steps did you take to try and increase model performance?

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

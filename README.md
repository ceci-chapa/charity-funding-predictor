# Charity Funding Predictor

## Overview

The purpose of this analysis is to help the non-profit foundation Alphabet Soup determine if applicants will be successful by creating an algorithm that can help predict the outcome. 

---

## Data Preprocessing

#### What variable(s) are considered the target(s) for your model?
The Is_Successful variable from the dataset was used as the target for the model.

#### What variable(s) are considered to be the features for your model?
The following variables from the dataset were used as the features: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT

#### What variable(s) are neither targets nor features, and should be removed from the input data?
After further analyzing the dataset, I believe STATUS, and SPECIAL_CONSIDERATIONS features could be removed. Compared to the rest of the other features, these two only had two unique values while the others contained four or more values. These two features would also not be considered the target since our target to determine success would be the Is_Successful variable. 


## Compiling, Training, and Evaluating the Model

#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
A total of three layers, three neurons, and two types of activation functions were used for the neural network. For the first and second layers the activation ReLu was applied. ReLu will only focus on the max(0, x) so this means the data will be processed in a simpler and faster manner to prevent exponential growth. Since Sigmoid focuses between 0 to 1, it was applied on the last layer for the output probability. 

#### Were you able to achieve the target model performance?

#### What steps did you take to try and increase model performance?


#### Summary
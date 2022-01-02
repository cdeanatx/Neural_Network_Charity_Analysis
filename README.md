# Neural Network Charity Analysis



## Overview of Analysis

The purpose of this analysis is to create neural networks to predict whether money loaned to charitable organizations will be used effectively.



## Results of Analysis

#### Data Preprocessing

- What variables are considered targets for the models? 

  **IS_SUCCESSFUL**

- What variables are considered features for the models?

  **APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS** (not in all models)**, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT**

- What variables are neither targets nor features and are removed from the model?

  **EIN, NAME**

##### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions were selected for the neural network models?

  - **Neurons - (80, 30), (160, 40, 80), (160, 80, 40, 20), (160, 80), (160, 120, 80, 40)**
  - **Layers - 2, 3, 4**
  - **Activation Functions - ReLu, SeLu**

- Was I able to achieve the target model performance?

  **Unfortunately not. I made slight alterations to the model between each iteration, but was unable to achieve the target performance.**

- What steps were taken to try and improve model performance?
  - **Increase number of neurons**
  - **Increase number of hidden layers**
  - **Increase/Decrease the numbers of bins for categorical features**
  - **Change the activation functions**
  - **Remove noisy features**

## Summary of Analysis

Overall, the best performance I was able to achieve in my models was 72.73% accuracy. In order to achieve a better accuracy score, a Hierarchical Bayesian model could be used. My recommendation for this model is due to its massive power in solving classification problems, like this one. The main downside to this model is its massive computational and time requirements.
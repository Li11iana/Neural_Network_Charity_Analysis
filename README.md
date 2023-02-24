# Neural_Network_Charity_Analysis

Implementation of Tensor Flow Neural Networks and deep learning for data analysis

## Overview

A nonprofit foundation aims to better predict when to invest by analyzing the data from 34,000 organizations that have received funding from Alphabet Soups.
Neural networks is an optimal tool when regular machine learning classifier model fall short. 

### Objective

Generate a binary classifier capable of predicting if an applicant will be successful if funded by Alphabet Soup.

## Results

### Data Preprocessing

* Models target selection

The target column selected is "IS_SUCCESSFUL" for the model. This column contains binary values that classify if a past applicant was able to successfully utilized the funds granted.

* Model's Variable selection 

All remaining variables but the column containing the name of applicant organization were chosen as variables.The name of the applicant contain no relevant information for the classification model.

### Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why?

![structure1](https://github.com/Li11iana/Neural_Network_Charity_Analysis/blob/main/structure1.png)

The initial model has created with 2 layers, composed of 80 and 30 neurons respectively. The number of neurons was selected based on the number of inpu features (43) that were used.

* Were you able to achieve the target model performance?

![accuracy1](https://github.com/Li11iana/Neural_Network_Charity_Analysis/blob/main/accuracy1.png)

At this moment, the models tested are still under the target performance value of 80%

* What steps did you take to try and increase model performance?

Based on the results of the first model the following steps were taken to improve its performance:

* Use of an additional layer

![structure2](https://github.com/Li11iana/Neural_Network_Charity_Analysis/blob/main/structure2.png)


A total of 3 layers, composed of 80, 30 and 20 neurons respectively were implemented. 
Model accuracy did not increase significatively

![accuracy2](https://github.com/Li11iana/Neural_Network_Charity_Analysis/blob/main/accuracy2.png)

* Use of a different activation function

![structure2](https://github.com/Li11iana/Neural_Network_Charity_Analysis/blob/main/structure2.png)


A different activation function was implemented in efforts to better describe the model's data pattern
Model accuracy did not increase significatively

![accuracy2](https://github.com/Li11iana/Neural_Network_Charity_Analysis/blob/main/accuracy2.png)

* Use of more layers and neurons

![structure3](https://github.com/Li11iana/Neural_Network_Charity_Analysis/blob/main/structure3.png)


As shown in the image above the total number of layers and neurons was auggmented in order to improve the model's accuracy
Model accuracy did not increase significatively

![accuracy3](https://github.com/Li11iana/Neural_Network_Charity_Analysis/blob/main/accuracy3.png)

### Summary

Current efforts to generate a classification model for the dataset have performed below the target accuracy of 80% but as shown in the images above, the accuracy obtained is close to that target.
Further examination of the dataset and exploration of other activation function is recommended to optimize the classification model.


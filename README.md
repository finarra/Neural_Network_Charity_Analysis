# Neural_Network_Charity_Analysis

## Overview
The main objective of this project is to create a binary classifier to predict succesful applicats funded by alphabet soup, by using a neural network model, preprocessing data, compiling and training the model , and then refactoring the code to optimize it's performance.

## Results
AFter succesfully preprocessing data and eliminating the columns which will not improve the model. The target is the succesful column, and EIN, NAME, STATUS were removed as they are not part of the model.

The model was trained and defined with two hidden layers, the first one with 80 neurons and second one with 30 neurons.

Later on the code was optimized to use five hidden layers, which each contained 80, 60, 40, 20 and 10 neurons.

After this changes the performance improved to a loss of 0.69 (previous 0.73) and accuracy improved to 0.53 (previous 0.43)

## Summary
The accuracy of the model was improved by adding 5 hidden layers. Still the overall performance may be further improved.

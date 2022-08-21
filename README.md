# Neural_Network_Charity_Analysis

## Overview of the analysis: 

The idea is to build an algorithm that can classify whether applicants will be succesful or not when applying for a funding program with Alphabet Soup.
For this, historic data will be used with thousands of previous organizations that have received the funding to be able to better predict the outcome of every new organization that comes in.
## Results: 
Data Preprocessing:
1. Target variables of the model:IS_SUCCESSFUL


2. Feature variables of the model:APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, and ASK_AMT.


3. Variables that should be removed:EIN, NAME, and SPECIAL_CONSIDERATIONS

Compiling, Training, and Evaluating the Model
4. How many neurons, layers and activation functions did you select and why?
* hidden_nodes_layer1 = 120
* hidden_nodes_layer2 = 15
* 2 layers
* LeakyReLU for layer 1 and 2, and Sigmoid for the output layer.
![Picture1](https://github.com/karen-trena/Neural_Network_Charity_Analysis/blob/main/Picture1.png)


5. Where you able to achieve the target?
No. I got from 72.55 on the base model to 72.61 on Attempt1, 72.64 on Attempt2, and 72.81 on Attempt3.
![Picture2](https://github.com/karen-trena/Neural_Network_Charity_Analysis/blob/main/Picture2.png)

6. What steps did you take to try and increase the model performance?
I tried registering the Accuracy everytime I did I change. I made 1 change at a time so I could really understand what was influencing the change. I tried changing the variables I selected for the model, the nodes for the hidden layers, and the activation functions.


## Summary: 
I didn´t get to the 75% Accuracy; I got 72.81%. Maybe I should had tried more layers. As Alphabet Soup continues giving more success cases or not, we will be able to continue tuning the model with more data coming in.We could also try other machine learning models such as Random Forest to increase accuracy. As a reminder, we know that random forests can be used for binary classification so it could be a good idea for this objective.

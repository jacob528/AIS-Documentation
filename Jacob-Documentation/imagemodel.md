# My Process Creating My First Practice Model

- To create this model, I used pytorch and other python libraries to create a model to analyze training data of digits and recognize it effectively

## Defining the Functions

- Log_SoftMax: This function applies a logarithm to the raw results of matrix multiplication of xb and the weights and biases
and converts them to probabilities, this helps compute the cost function

- Model: This sets up the model by taking in a parameter of a small sample of data xb (64 in the first case) and doing a matrix multiplication with that and the weights, and after adding it to the vector of biases (one bias for each digit 0-9). The model returns the log_softmax of this result.

- NLL (Negative Log Likelihood): This is the actual cost function that is used to gauge the correctness of the model. The goal is to minimize this number to increase the accuracy of the model. 

- Accuracy: This function takes two parameters, out and xb (the training data) and returns the accuracy as a decimal.

## Running Through The Code

- The code first reads in the data and then prints the data. 
- It creates a tensor that maps x and y of the model in the valid bounds
- Define weights and biases
- Give predictions by modeling the dataset without any backpropogation
- With that my accuracy is very low (0.17)


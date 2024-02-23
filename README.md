# MNIST Neural Network


This  project is about training a neural network to classify the digits based on the MNIST data set.



## Repo Structure

The  repo has three files as follows

- model .py
- utils .py
- S5-3.ipynb


### model .py 
This file  has the definition of neural network which include number of convolution layers , fully connected layers.

#### Net.class
- This has the definition of neural network and  forward function which connects all the convolution layers , activation functions and fully connected layers.

### utils .py 

#### train 
- This module trains the dataset and calculates the loss and accuracy for the same.

#### test 
- This module tests the dataset and calculates the loss and accuracy for the same

#### plot 
- This module plots a graph for training loss,test loss,training accuracy and test accuracy from the data obtained from test and train modules.

### S5-3.ipynb



It is a jupiter notebook which actually trains and tests the model using the modules defined earlier.


####  Code Block 1 

- Imports the  necessary modules 

#### Code Block 2

-  Assigns the device based on the GPU availability 

#### Code Block 3

- Train and test transforms are defined

#### Code Block 4

- Downloads the train and test datasets


#### Code Block 5

- Train and Test datasets are loaded to a torch object ,this helps us in training and testing as it converts the dataset to a desired datatype.

#### Code Block 6

- Plots first 12 entries present in the shuffled training dataset.

#### Code Block 7
- Imports classes and functions from model .py and util .py

#### Code Block 8

- Defining few parameters to plot  accuracy and loss graphs


#### Code Block 9

- Class in model is initialized
- optimizer and scheduler are defined
- For each epoch training and testing is done. The loss and accuracy are also noted.


#### Code Block 10

- Using the plot function from utils .py ,training loss,test loss,training accuracy and test accuracy plots are generated




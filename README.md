# AML-Assignment
Assignments realized for the master course of Advanced Machine Learning for University Milano Bicocca

## Assignment 1
The assignment consists in the prediction of the price (same name as the target variable in the dataset) of a private room/entire apartment using a neural network.

The dataset includes all the information you need to learn more about hosts, geographic availability, and necessary metrics of Airbnb apartments in New York City in 2019.

The provided data comprises the training set that can be used for the training (and eventually for the validation) and the unlabelled test set.

In order to be evaluated, each student should submit a zip file named Nome_Cognome_Matricola_assignment1.zip containing all and only

- the source code;
- a brief PDF or WORD report (1 or 2 pages) with some motivations about the choices on the data processing, the number and dimension of the layers, the activation functions and the loss functions, and some comments about the results.
- a txt file named Nome_Cognome_Matricola_score1.txt, where each line corresponds to the prediction of the instances of the test set. The file should contain only this column and with no header. In the case of standardization/normalization of the target variable, scale back the predictions to the original representation.

## Assignment 2
The assignment consists in the prediction of default payments using a neural network. 

The dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005. 

The provided data comprises the training set that can be used for the training (and eventually for the validation) and the unlabelled test set.

In order to be evaluated, each student should submit a zip file named Nome_Cognome_Matricola_assignment2.zip containing all and only:

- the source code;
- a brief PDF or WORD report (2 or 3 pages) or Jupyter notebook reporting:
  1. The resolution of the problem of supervised classification with a traditional neural network  (Fully-connected Neural Network) with some motivations about the choices on data processing, number and dimension of the layers, optimization algorithms and some comments about the results (as seen in class)
  2. The investigation on the effect of the use of regularization in terms of result and change in the weights of the neural network (as seen in class)
- a txt file named Nome_Cognome_Matricola_score2.txt, where each line corresponds to the prediction (0/1 class) of the instances of the test set. The file should contain only one 0/1 column and with no header.

## Assignment 3
The task of the assignment #3 is the design of a CNN architecture and its training.

Input dataset: MNIST digits (input size 28x28x1, number of classes: 10).

The CNN has to be designed with the aim of reaching the maximum possible accuracy on the test set, with the hard constraint of a maximum of 7K learnable parameters. 

The report must contain:
- a description of the designed architecture
- the parameters count for each layer
- the hyper-parameters used for training (batch size, learning rate, optimizer, number of epochs, etc)
- a plot of the training and validation loss/accuracy 
- classification performance on training, validation (if available) and test set

## Assignment 4
The task of this assignment is Transfer Learning using a CNN pretrained on IMAGENET.

The suggested architecture is the VGG16.

The CNN should be used as fixed feature extractor on a new task of your choice containing a number of classes in the range from 2 to 10. 

The report must contain:
- a description of the new task and on the dataset used
- the use of the pretrained CNN as feature extractor considering different layers (at least 3 different choices)
- the chosen "classical" classifier
- for each transfer learning experiment:
  - the details about the chosen layer
  - the plot of the classification performance on train/val/test for the different layers considered
  - the hyper-parameters used for training the "classical" classifier

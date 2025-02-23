# Linear Regression with PyTorch - a Typical Workflow
a typical workflow for a simple linear regression problem with PyTorch

PyTorch is a very popular machine learning library used to solved all kinds of problems, including regression and classification. In this article, we'll have a look at a typical workflow for a simple linear regression problem. To keep things simple, we'll stick to just the necessary elements, from importing the required libraries to saving and loading a trained model.

There are four major steps to follow during a machine learning process:

1. Data preparation
2. Model building
3. Model training
4. Model evaluation
   
Additionally, we'll save the working model, load it back in and test if it still works as expected.

## Data Preparation
In this part, we'll create the parameters and data points. We'll split the data into a training set and a test set. We'll visualize the data.

![image](https://github.com/user-attachments/assets/982aaed7-69d7-4310-b018-91a1a9a62319)

## Model Building
In this part, we'll build a linear regression model using nn.Parameter. We'll make predictions. 

![image](https://github.com/user-attachments/assets/7ff1d8e6-9545-49d7-94dc-a21356c20a71)

## Model Training
In this part, we'll pick a loss function and optimizer. We'll create the training loop and testing loop and we'll train the model.

![image](https://github.com/user-attachments/assets/f80daf3b-0138-4040-ba49-7d379f0e5ae0)

## Model Evaluation
In this part, we'll evaluate the model and train it for more epochs to improve the result.

![image](https://github.com/user-attachments/assets/2b6b5486-a1b8-499d-91fc-5d939be84ffa)

## Saving and Loading the Model
In this part, we'll save the parameter dictionary, then load it back in and create a new model with it.

![image](https://github.com/user-attachments/assets/72b10428-6b7e-4914-94a5-597a29e210b1)

## Recreating the Model Using a Simple Neural Network
In this part, we'll recreate all the steps with slight modifications and create yet another model.

![image](https://github.com/user-attachments/assets/1f018d4b-2089-4cb4-ac78-087cb6001253)



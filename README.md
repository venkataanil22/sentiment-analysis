# Deploying a Sentiment Analysis Model using SageMaker

The notebook and Python files provided here, once completed, result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker, the mini-project, Sentiment Analysis using XGBoost, should provide enough background.

# Project Overview
This is the final solution of the project 'Sagemaker Deployment' which consists in deploying a Sentiment Analysis model using RNN in the Amazon AWS SageMaker tool. The notebook and Python files provided here result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews.

In the final architecture AWS API Gateway and AWS Lambda functions is used as well. The application architecture diagram is:

![](Web%20App%20Diagram.svg)

You can find the original code without solutions in the original Udacity SageMaker Deployment repository.

This project assumes some familiarity with SageMaker, the IMDB Sentiment Analysis using XGBoost mini-project (which can be found in the original repository) should provide enough background.

# Instructions to execute in sagemaker
Clone the repository.
	git clone https://github.com/venkataanil22/sentiment-analysis
# Open the SageMaker Project.ipynb file.
	jupyter notebook SageMaker Proejct.ipynb
Read and follow the instructions! You can find and download the dataset for this project in the notebook.
# General Outline
Step 1: Downloading the data 
Step 2: Preparing and Processing the data 
Step 3: Upload the data to S3 
Step 4: Build and Train the PyTorch Model 
Step 5: Testing the Model 
Step 6: Deploying the model for testing 
Step 7: Use the model for testing 
Step 6 Deploy the model for the web app 
Step 7 Use the model for the web app

# Libraries
The list below represents main libraries and its objects for the project.

1. Amazon SageMaker (Build, train, and deploy a model)
2. Tensorflow (LSTM classifier)

# Delete the Endpoint
Remember to always SHUT DOWN YOUR ENDPOINT if you are no longer using it. You are charged for the length of time that the endpoint is running so if you forget and leave it on you could end up with an unexpectedly large bill.

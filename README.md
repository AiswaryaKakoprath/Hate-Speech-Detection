# Hate Speech Detection

Welcome to the Hate Speech Detection repository! This project focuses on detecting hate speech using natural language processing (NLP) and machine learning techniques. The best-performing model for hate speech detection, Logistic Regression, has been identified and implemented. Additionally, a web application using Flask has been created to facilitate hate speech detection in real-time.

## Contents

1. [Introduction](#introduction)
2. [Model](#model)
3. [Dataset](#dataset)
4. [Usage](#usage)
5. [Web Application](#web-application)

## Introduction

Hate speech detection is a critical task in ensuring a safe and inclusive online environment. This project aims to develop robust models capable of automatically identifying hate speech in text data across various platforms, including social media, forums, and comment sections. By leveraging NLP techniques and machine learning algorithms, we strive to create effective solutions for combating hate speech online.

## Model

The logistic regression model has been identified as the best-performing model for hate speech detection. Logistic regression is a simple yet powerful linear model that is well-suited for binary classification tasks. In this project, logistic regression is trained on labeled examples of hate speech and non-hate speech text samples to classify new text data.

## Dataset

The dataset used for training and evaluation consists of labeled examples of hate speech and non-hate speech text samples. This dataset is carefully curated to ensure diversity and relevance to real-world scenarios. Data preprocessing techniques are applied to clean and prepare the text data for training the logistic regression model.

## Usage

To utilize the logistic regression model for hate speech detection, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies specified in the `requirements.txt` file.
3. Train the logistic regression model using the provided dataset or your custom dataset.
4. Evaluate the model's performance using appropriate evaluation metrics.
5. Save the trained logistic regression model for future use or deployment.

## Web Application

A web application is created using Flask to provide a user-friendly interface for hate speech detection. Users can input text data, and the deployed logistic regression model will classify it as hate speech or non-hate speech in real-time. The web app enhances accessibility and usability, making hate speech detection accessible to a wider audience.

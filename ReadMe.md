# Identifying Entites in Healthcare Data Using Natural Language Processing

## Problem Statement
BeHealthy has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions. So, companies like ‘BeHealthy’ are providing medical services, prescriptions and online consultations and generating huge data day by day.

## Datasets
There are four datasets provided to you to process, which are as follows:
train_sent
test_sent
train_label
test_label

## Actions:
1. You need to process and modify the data into sentence format. This step has to be done for the 'train_sent' and ‘train_label’ datasets and for test datasets as well.
2. After that, you need to define the features to build the CRF model.
3. Then, you need to apply these features in each sentence of the train and the test dataset to get the feature values.
4. Once the features are computed, you need to define the target variable and then build the CRF model.
5. Then, you need to perform the evaluation using a test data set.
6. After that, you need to create a dictionary in which diseases are keys and treatments are values.


There are eight major tasks we have to perform. They are as follows:
1. Data preprocessing
2. Concept identification
3. Defining the features for CRF
4. Getting the features words and sentences
5. Defining input and target variables
6. Building the model
7. Evaluating the model
8. Identifying the diseases and predicted treatment using a custom NER

## Python Packages Used
- Numpy - version 1.23.5
- Pandas - version 1.5.3
- Matplotlib - version 3.7.1
- Seaborne - version 0.12.2
- Scikit-learn - version 1.2.2
- sklearn-crfsuite - version 0.3.6
- Spacy - Version: 3.7.4

## Contributor
Created by [Anupam Maiti](https://github.com/dynamicanupam) - feel free to contact me!



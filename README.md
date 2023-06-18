# Syntactic Processing Assignment

## Identifying Entities in Healthcare Data
## Problem Statement
‘BeHealthy’ aims to connect the medical communities with millions of patients across the country.  ‘BeHealthy’ has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions. You have been given such a data set in which a lot of text is written related to the medical domain.  As you can see in the dataset, there are a lot of diseases that can be mentioned in the entire dataset and their related treatments are also mentioned implicitly in the text. You need to build a custom NER to get the list of diseases and their treatment from the dataset.

In this assignment, you need to perform the following broad steps:
- You need to process and modify the data into sentence format. This step has to be done for the 'train_sent' and ‘train_label’ datasets and for test datasets as well.
- After that, you need to define the features to build the CRF model.
- Then, you need to apply these features in each sentence of the train and the test dataset to get the feature values.
- Once the features are computed, you need to define the target variable and then build the CRF model.
- Then, you need to perform the evaluation using a test data set.
- After that, you need to create a dictionary in which diseases are keys and treatments are values.
- There are eight major tasks that you need to perform to complete the assignment. They are as follows:
-- Data preprocessing
-- Concept identification
-- Defining the features for CRF
-- Getting the features words and sentences
-- Defining input and target variables
-- Building the model
-- Evaluating the model
-- Identifying the diseases and predicted treatment using a custom NER


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Lending club wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  It can utilise this knowledge for its portfolio and risk assessment. 
- We are using Loan data given by Lending Club.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We found Negatively correlated features with Loan status as Defaulters.
  They are home_ownership, annual_inc and verification_status.
- We found Postively correlated features with Loan status as Defaulters.
  They are term, int_rate, grade. 
- In detail conclusion can be found in the pdf.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.20.3
- matplotlib - version 3.4.3
- python 3.9
- pandas - version 1.3.4
- pycrf
- sklearn
- spacy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by upgrad NLP assignment on syntactic processing.


## Contact
Created by @rahul2july - feel free to contact us!

#### Contributors
-Rahul Gupta

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

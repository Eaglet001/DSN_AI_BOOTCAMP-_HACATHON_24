# DSN_AI_BOOTCAMP_HACKATHON_24
# Heart Disease Prediction

## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [Feature](#feature)
- [Model](#model)
- [Acknowledgements](#acknowledgements)

## Introduction
The challenge at hand revolves around the creation of a sophisticated predictive model aimed at determining the likelihood of an individual having heart disease. As one of the leading causes of global mortality, detecting heart disease in its early stages is pivotal for enhancing patient outcomes and halting its progression. The conventional diagnostic methods often come with substantial costs and time requirements. Thus, there exists a pressing need for a cutting-edge predictive model that can evaluate the risk of heart disease utilizing easily accessible patient information.

## Objective
The objective of this challenge is to design and build a predictive model capable of accurately determining the probability of an individual having heart disease. The focus is on leveraging machine learning techniques to create a model that can analyze relevant features and provide reliable predictions. The model should demonstrate high accuracy and generalizability, ensuring its effectiveness on new, unseen data.


## Feature
The dataset contained no missing values,a column data type was changed to make all data int64 
train_df["old peak"] = train_df["oldpeak"].astype('int64')
futhermore the dataset was standardized using StandardScaler before fitted into the model


## Model
The model is built using Random Forest and Xgboost as both were stacked for better result .
The model had an accuracy score of 0.8199863107460643

The model performance on the public and private leaderboard was 0.809750927, placing 152 in the competition out of over 400 participants , this secured me a spot in the prestigious DSN all expense paid bootcamp


## Acknowledgements
- All contributors and participants of the hackathon.
- Data Science Nigeria(DSN) for such wonderful Hackathon

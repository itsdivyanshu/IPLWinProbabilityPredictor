# IPL Winning Percentage Predictor

This project is an IPL (Indian Premier League) winning percentage predictor based on machine learning. It predicts the winning percentage of IPL teams using historical data.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Results](#Results)
- [Front-End](#Front-end)

## Introduction

The IPL Winning Percentage Predictor is designed to analyze past IPL match data and predict the winning percentage of teams in future matches. It uses machine learning algorithms to process historical data, extract relevant features, and make predictions.

## Features

- Historical IPL match data
- Winning percentage prediction for IPL teams
- User-friendly interface

## Dataset

The Dataset we used is of all the matches and all the events happen in all the deliveries happen from 2008-2019
It is easily available at Kaggle.

I preprocessed the data and made the dataset from
![image](https://github.com/modychief/IPl_Match_percent_Predictor/assets/112490642/23853fb9-f6c6-4cde-97e6-d0111c8ef22f)
![image](https://github.com/modychief/IPl_Match_percent_Predictor/assets/112490642/62fcd3db-60ea-4bed-ad9e-a9d2956b23f1)

to this
![image](https://github.com/modychief/IPl_Match_percent_Predictor/assets/112490642/5faa71f4-d038-4581-8990-6c0292f530c2)


## Model Training

The IPL Winning Percentage Predictor uses machine learning algorithms called Logistic Regression for prediction, you can also use Ensemble Learning But it overfits the data, so use carefully.



## Result

Accuracy for the Logistic regression is ![image](https://github.com/modychief/IPl_Match_percent_Predictor/assets/112490642/48346414-c79b-4845-8923-8a4bcdbb2f0e)

and match scenario is covered over by over and it comes like so -
![image](https://github.com/modychief/IPl_Match_percent_Predictor/assets/112490642/76031305-73e7-401e-b6c3-4b30d5855371)

Graph

![image](https://github.com/modychief/IPl_Match_percent_Predictor/assets/112490642/dd761363-a648-434e-a6ee-32e0b1e9932f)


## Front end
I made a front end for this model to host it using streamlit and it looks like so - 
![WhatsApp Image 2023-05-29 at 20 45 33](https://github.com/modychief/IPl_Match_percent_Predictor/assets/112490642/ce824f10-257e-4954-a047-544bb5459622)

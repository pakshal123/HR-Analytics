# HR Analytics: Prediction of Employee Attrition

## BUDT704-0506: Data Processing and Analysis in Python Project (Fall 2022)

### Group: 14

#### Team Members:
- Sri Sai Alekya Ghanta
- Sahil Kumar Rao
- Sarvesh Rajwade
- Varun Shrivastava
- Pakshal Shah
- Jarrar Haider

### Under the guidance of:
Dr. Peng Huang

## Table of Contents

1. [Background](#background)
2. [Introduction](#introduction)
3. [Mission Objectives](#mission-objectives)
4. [Data Overview](#data-overview)
5. [Approach & Methodology](#approach-and-methodology)
   - [Exploratory Data Analysis](#exploratory-data-analysis)
   - [Data Preprocessing](#data-preprocessing)
   - [Class Imbalance & Upsampling](#class-imbalance--upsampling)
   - [Model Building](#model-building)
   - [Model Performance Comparison](#model-performance-comparison)
6. [Results](#results)
7. [References](#references)

## 1. Background

More than 4.25 million people in America quit their jobs in January 2022, up from 3.3 million in 2021, as reported by U.S. Bureau of Labor Statistics (BLS). The expense of replacing an existing employee is around one and a half to two times the annual salary. Recognizing the causes and predicting employee attrition is crucial for organizational success.

## 2. Introduction

This project utilizes HR Analytics data to predict employee attrition. The dataset, obtained from Kaggle, contains information about current and former employees.

## 3. Mission Objectives

The goal is to provide insights to Founders, CEO, Leadership Team, and HR Department about factors leading to employee attrition and predict attrition beforehand.

## 4. Data Overview

The dataset has 14,999 observations and 10 features. Key predictors include satisfaction level, last evaluation, number of projects, average monthly hours, time spent in the company, work accident, promotion in the last 5 years, department, and salary.

## 5. Approach and Methodology

### 5.1 Exploratory Data Analysis

- Employee statistics
- Last evaluation vs satisfaction level
- Average monthly hours vs satisfaction level
- Attrition statistics based on workload
- Employees left proportion by department
- Correlation analysis

### 5.2 Data Preprocessing

- Handling duplicate values
- Handling missing values
- Handling categorical variables
- Removing unnecessary features

### 5.3 Class Imbalance & Upsampling

The dataset is imbalanced; upsampling is performed to balance the class distribution.

### 5.4 Model Building

Four machine learning models are built:
1. Logistic Regression
2. RandomForest
3. Decision Tree
4. Naive Bayes

### 5.5 Model Performance Comparison

- Confusion matrix
- ROC Curves
- Classification report

## 6. Results

- Insights gained through EDA
- Important features identified
- Model performance analysis

## 7. References

1. Kaggle Dataset Source: [HR Analytics Job Prediction](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-jobprediction?resource=download&select=HR_comma_sep.csv)
2. [Employee Retention Statistics and Insights 2022](https://peoplemanagingpeople.com/articles/employee-retention-statistics/)

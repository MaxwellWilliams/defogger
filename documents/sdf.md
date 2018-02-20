# Defogger
**Members (current): Max Williams**

## 1.0 Project Status Sheets

## 2.0 Preliminary Project Proposal

## 3.0 Project Proposal and Slides

Defogger is a data science and machine learning based project that will provide insight into the past, present, and future trends of a dataset.  The data source being used is yet to be determined, but will most likely focus on crime data from the LAPD, city census data, or flu data.  Software such as Pandas, tensorflow, jupyter notebooks, and a database are expected to be used, and additional processing power may be required for advanced modeling and prediction.

This project is justified for this class because it meets all key requirements.  The storing, manipulation, and analysis of the data will require use of knowledge from classes such as data structures, algorithms, and databases.  Additionally, this project will involve machine learning and elements of data science which will challenge and expand my current understanding.  The large quantity of data involved in this project will be analyzed in many ways to find any possible correlations, which will require thorough and repeatable analysis which will be challenging and time intensive.  The combination of all these characteristics and my interest in expanding my knowledge of the subject make this project justified for this class.

![Proposal Presentation Slides](https://github.com/maxwellwilliams/defogger/blob/master/documents/proposal_presentation.pdf)

## 4.0 Software Development Plan

## 5.0 Requirements Document

### 5.1 Introduction

### 5.2 Functional Requirements

#### 5.2.1 General Analysis

The general analysis portion of this project provides the user with a reusable way to breakdown and statistically analyze crime data from the LAPD in both numerical and graphical ways.  The general analysis can be re-run to update analysis based on new or alternate data in the same format.

##### 5.2.1.1 The general analysis shall run on any dataset with the same format.

##### 5.2.1.2 The general analysis shall integrate with LA City's dataset API.

##### 5.2.1.3 The general analysis shall provide reusable code segments that can be run non-sequentally.

##### 5.2.1.4 The general analysis shall proivide graphical breakdowns, summary and analysis of crime data.

##### 5.2.1.5 The general analysis shall proivide statistical breakdowns, summary and analysis of crime data.

#### 5.2.2 Machine Learning

The machine learning portion of this project provides the user with models based on LAPD crime data.  These models could be used for data prediction or to identify outliers.

##### 5.2.2.1 Machine learning shall run on any dataset with the same format.

##### 5.2.2.2 Machine learning shall integrate with LA City's dataset API.

##### 5.2.1.3 Machine learning shall provide several models using different values as vairables.
Vairables used for modeling:
  - Crime
  - Location
  - Date (Year, Month, Day of week)
  - Time

### 5.3 Performance Requirements



### 5.4 Environment Requirements

#### 5.4.1 Hardware Requirements

#### 5.4.1.1 General analysis shall require only a standard computer and access to the internet.

#### 5.4.1.2 Machine learning may require a GPU or cloud computing based on its complexity.

#### 5.4.2 Software Requirements

#### 5.4.2.1 General analysis will require several base software components to build the reqired execution environment.
Requirements (Subject to change):
  - python3
  - pip3
  - virtualenv
  - python3-matplotlib

#### 5.4.2.2 Machine learning may require several software components to build models.
Requirements (Subject to change):
  - python3
  - pip3
  - virtualenv
  - tensorflow
  - scikit-learn
  - deeplearn.js

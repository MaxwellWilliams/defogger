# Defogger
**Members: Max Williams**

## 1.0 Project Status Sheets

### Project Status 2/19/2018

#### Accomplishments since last report:
  - Established environment and software requirements for general analysis.
  - Setup Jupyter notebook which imports data from the LA City's dataset database.
  - Broke down crime data based on crime code, providing statistical and grapical analysis.
  - Broke down the occurances of a specific crime into monthly categories.
  - Began research for machine leaning with tensorflow, scikit-learn, and deeplearn.js.

#### Scheduled tasks to be done by next report:
  - Wrap-up a majority of the analysis for the general analysis component.
  - Determine which machine learning library to build inital models with.
  - Setup environment for machine learning and begin creating models.

#### Noteworthy risks, concerns, or problems:
  - Need to learn more about machine learning, and the differences between platforms.
  - The processing power required for machine learning may require a GPU, which means I will need to buy some hardware and setup my dekstop.

## 2.0 Preliminary Project Proposal

## 3.0 Project Proposal and Slides

Defogger is a data science and machine learning based project that will provide insight into the past, present, and future trends of a dataset.  The data source being used is all LAPD crime data from 2010 to present.  Other datasets considere were city census data, and flu data.  Software such as Pandas, tensorflow, jupyter notebooks, and a database are expected to be used, and additional processing power may be required for advanced modeling and prediction.

This project is justified for this class because it meets all key requirements.  The storing, manipulation, and analysis of the data will require use of knowledge from classes such as data structures, algorithms, and databases.  Additionally, this project will involve machine learning and elements of data science which will challenge and expand my current understanding.  The large quantity of data involved in this project will be analyzed in many ways to find any possible correlations, which will require thorough and repeatable analysis which will be challenging and time intensive.  The combination of all these characteristics and my interest in expanding my knowledge of the subject make this project justified for this class.

![Proposal Presentation Slides](https://github.com/maxwellwilliams/defogger/blob/master/documents/proposal_presentation.pdf)

## 4.0 Software Development Plan

### 4.1 Plan Introduction

This Software Development Plan provides the details of the planned development for the defogger project which provides a reusable framework and code segments for the analysis and prediction of LAPD crime data.

#### 4.1.1 Project Deliverables

- Project Proposal Document
  - A document proposing the project, identifying its scope, core components, and justification.
- Requirements Document
  - A document which will identify the functional, performance, and environment requirements for this completed project, and the degree to which each requirement needs to be meet.
- Software Development Plan
  - A document which will describe the development processes and documents that will be used while completing this project.
- Defogger
  - The product delieverd as specified by the Project Proposal, Requirements, and Software Development documents.
- Presentaion of Defogger
  - A presentation and poster of Defogger, summarizing the requirements of the project and highlighting its functionality.  Demonstrations of defogger may also be included in this presentation.
  
### 4.2  Project Resources

#### 4.2.1 Hardware Resources

- Laptop or Desktop with sufficient memory and computation power to store the entire dataset, and run calculations ranging from simple to complex using it.

#### 4.2.2 Software Resources

- Atom text editor (or equivalent)
- Python3
- pip3
- virtualenv
- jupyter
- pandas
- matplotlib
- scikit-learn
- tensorflow

### 4.3  Project Organization

- Dataset Research
  - Research potential datasets (Crime Data, Flu Data, Census Data), and determine which data can be easily and reliably obtained for this project.
  - Implement python script for collecting this data.
- General Analysis
  - Research tools such as jupyter, pandas, and matplotlib.
  - Using the dataset collected in the previous section, implement reusable functions which calculates and visualizes varying distributions of this crime data.  (Reusable means this code can be re-run with an updated dataset as long as it is in the same format.)
  - The goal of this section is to build the tools to illustrate and identify trends within the dataset, and identify some trends within the dataset.
- Machine Learning
  - Resarch machine learning tools such as scikit-learn and tensorflow.
  - Using the dataset collected in the first section, implement reusable machine learning functions which identify trends within the dataset, and are able to provide some level of prediction of future crime data.  (Reusable means this code can be re-run with an updated dataset as long as it is in the same format.)
  - The goal of this section is to identify as many trends within the data as possible, and use them to predict future trends or datasets.

### 4.4  Project Schedule

#### 4.4.1 PERT Chart

![PERT Chart](https://github.com/maxwellwilliams/defogger/blob/master/documents/pert_chart.jpg)

#### 4.4.2 Task / Resource Table

- Dataset Research
  - Sufficient laptop/desktop with internet access
  - python3 / pip3
  - virtualenv
- General Analysis
  - Sufficient laptop/desktop with internet access
  - Dataset Research
  - python3 / pip3
  - virtualenv
  - jupyter
  - pandas
  - matplotlib
- Machine Learning
  - Sufficient laptop/desktop with internet access
  - Dataset Research
  - python3 / pip3
  - virtualenv
  - scikit-learn
  - tensorflow

## 5.0 Requirements Document

### 5.1 Introduction

Defogger will analyze LAPD crime data in two main components, General Analysis and Machine Learning.  The general analysis component will breakdown and statistically analyze LAPD crime data in both numerical and graphical ways.  The goal of this portion is to identify general trends within the data.  The machine learning component will build models that will charcterize trends within this data for further analysis and prediction.  The goal is to provide models of different subsets and complexity to uncover and predict trends.

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

Depending on the complexity of the analysis the performance of this application will vary from task to task.  Therfore, beyond reasonable constraints performance requirements cannot be stated.

#### 5.3.1 Output Times

##### 5.3.1.1 The general analysis code segments and functions should return an output in less than 5 minutes.

##### 5.3.1.2 Machine learning should return a model in less than 24 hours.

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

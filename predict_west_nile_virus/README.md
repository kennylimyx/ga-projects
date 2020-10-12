#GA DSI15 Project 4: Predict West Nile Virus

---

### Overview
The aim of this project is to provide Department of Public Health with a high performing classifier to determine the most cost effective plan to implement vector control.

---

### Problem Statement
Disease And Treatment Agency, division of Societal Cures In Epidemiology and New Creative Engineering (DATA-SCIENCE) is a government body dedicated to protecting its people from infectious diseases. We have been asked to consult and generate insights on where and when, the Department of Public Health (DOPH) should conduct vector control to prevent the spread of the West Nile Virus (WNV).

To do so,  we will be looking at the traps, weather and spray datasets, conduct exploratory data analysis and finally, build a classifier that is able to predict which areas will have the presence of the WNV. We will be evaluating our success using several classification metrics including, sensitivity, recall, f1 score and the ROC AUC.

Due to the high cost of vector control, our ability to identify high risks areas through our classifier and weigh the pros and cons through a cost benefit analysis will allow the DOPH to make a calculated and informed decision.

---

### Executive Summary
DATA-SCIENCE has been invited as a consultant to DOPH to help determine the most cost efficient way to implement vector control, to curb the rise of WNV. To do so, we have built a classifier to predict areas with high risks of a resurgence.

Our classifier was successful in predicting at an above 80% ROC AUC score. We have also included 3rd party research on the costs of vector control, treatment as well as costs to the economy in terms of productivity. These will help us in our cost benefit analysis and deploy the most effective plan to deploy pesticudes throughout the city.

---

### Notebooks:
- [Data Import and Cleaning](./book1_train_test_data_import_cleaning.ipynb)
- [EDA](./book2_eda.ipynb)
- [Modeling and Recommendations](./book3_feature_engineering_modeling.ipynb)

---

### Learning Objectives
- Learn to work together as team
- Adopt thorough documentation best practices
- Clean and preprocess data
- Describe my data with the written language as well as data visualisations
- Identify patterns and trends, using code and statistical knowledge
- Preprocess and use models to make predictions
- Translate findings into recommendations
- Convey the key message to both semi-technical and technical audience

---

#### Deliverables
For this project, there will be 3 components:
- 3 x Jupyter notebooks that contains the codes and analysis commentary of the process.
- This README file that provides an introduction to and overview of your project.
- 1 x Presentation slides in pdf format

You can find these here: https://git.generalassemb.ly/dorafoong/project-4.git

---

### Datasets
4 datasets in separate csv-files were saved, containing:
- train_clean.csv
- test_clean.csv
- weather_clean.csv
- spray_clean.csv

---

### Data Description
- The description for the datasets, can be found here: https://www.kaggle.com/c/predict-west-nile-virus/.


---
### Conclusions and Recommendations
To conclude, we were asked to consult and generate insights on if the WHEN and WHERE, the Department of Public Health (DOPH) should conduct vector control to prevent the spread of the West Nile Virus (WNV).

After data cleaning, EDA and feature engineering, we preprocessed our data by scaling and balancing our data. We then used cross validation to select the model. Once done, we tuned the hyperparameters to generate the best scores. Using the optimum parameters, we scored them on the training data, using a range of classification metrics including f1 accuracy score. Since false positive and false negatives were important to us, we chose the model with the highest ROC AUC score and scored our optimal model with the test data. Finally, our classifier achieved a test score of 0.834, which means that it correctly classified text data 83.4% of the time.

We then conducted cost benefit analysis on whether aerial spraying is a cost effective solution. We concluded that the economic costs of not spraying far outweighed the cost of the spray, especially in a city as dense as Chicago.

Our recommendation, based on the model's predictions and feature importance, is that the vector control should be conducted:

- sunrise, where the mosquitos are most active
- 1-2 weeks before the onset of warmer and humid months
- focus on areas with high populations of CULEX RESTUANS and CULEX TERRTANS
- areas predicted to have the WNV present, according to predictions map

With these, we will be able to provide better insights to the DOPH to help with their mission to reduce the spread of West Nile Virus.

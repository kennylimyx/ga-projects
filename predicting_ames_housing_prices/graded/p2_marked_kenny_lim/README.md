#GA DSI15 Project 2: Ames Housing Data and Kaggle Challenge

---


### Overview
The aim of this project is to provide our real estate investment team with recommendations on the investment strategy. I will be basing my recommendations on the Ames Housing data from 2006-2010, as well as some third party research.

---

### Problem Statement
Our real estate investment company has newly set up a data science team. The main feedback from the investment team is trouble identifying property with investment value due to the myriad of factors. We are tasked to find out what are strong predictors of housing prices. To do so, we will be examining Ames housing data. We hope to be able to predict housing prices and therefore identify highly demanded features by potential homeowners so as to provide recommendations to guide the company's investment strategy.

---

### Executive Summary
We have been tasked to predict housing prices so as to generate actionable insights for the organisation to achieve larger margins in their investment strategy. In order to achieve our goals, we will be performing data cleaning, feature engineering, EDA, feature selection and lastly several regression models to predict sale prices. Based on an accuracy score, the best model will be evaluated and chosen to predict sale prices. Having mirrored the market, we can then find out which are the strong predictors of sale prices. With this information, the company is able to locate properties with the favoured features and flip them for profit, generating value for the management, shareholders and of course customers.

---

### Notebooks:
- [Data Cleaning and Feature Selection](./book1_data_cleaning_feature_engineering.ipynb)
- [EDA and Feature Selection](./book2_eda_feature_selection.ipynb)
- [Preprocessing, Modeling and Recommendations](./book3_preprocesing_modeling_recommendations.ipynb)

---

### Learning Objectives
- Adopt thorough documentation best practices
- Import and clean data
- Describe my data with the written language as well as data visualisations
- Identify patterns and trends, using code and statistical knowledge
- Preprocess and use models to make predictions
- Translate findings into recommendations
- Convey the key message to a non-technical audience

---

#### Deliverables
For this project, there will be 3 components:
- 3 x Jupyter notebooks that contains the codes and analysis commentary of the process.
- This README file that provides an introduction to and overview of your project.
- 1 x Presentation slides in pdf format

You can find these here: https://git.generalassemb.ly/kennylimyx/projects/tree/master/project_2

---

### Datasets
3 datasets in separate csv-files were used, containing:
- train.csv that contains the training data
- test.csv that contains the test data
- sample_sub_reg.csv that contains the submission format for Kaggle

5 datasets in separate csv-files were saved, containing:
- train_clean.csv that contains the training data that was cleaned together with the test data, with new variables
- train_clean_2.csv that contains the training data that was cleaned after the test data was separated
- test_clean.csv that contains the test data that was cleaned, with new variables
- test_pred.csv that contains the predicted sale prices based on test data and was submitted on Kaggle
- combined_clean.csv that contains both train and test data that was clean together, with new variables


---

### Data Description
Ames Housing Dataset
Please find details of the Ames Housing Dataset here: http://jse.amstat.org/v19n3/decock/DataDocumentation.txt

---

#### Additional Data
Links to other 3rd party research will be included here:
https://datausa.io/profile/geo/ames-ia/#housing
http://www.usa.com/ames-ia-natural-disasters-extremes.htm
https://en.wikipedia.org/wiki/Flipping

---
### Conclusions and Recommendations
Our problem statement was to be able to predict housing prices through the use of a regression model and therefore identify highly demanded features by potential homeowners so as to provide recommendations to guide the company's investment strategy.

Through data cleaning, EDA, feature engineering and selection, we managed to run our data through a lasso regression model to produce predicted sale prices. Through the use of the R2 metric, we evaluated our model and inferred that the relationship between our selected features and sale price accounts for 87.4% of the variation.
With a high level of certainty, we were then able to identify strong predictors of price in choosing properties to invest in. These houses should typically:
- have a large living area
- be in specific neighbourhoods
- have a focus on the quality of the build of the house.

With the above recommendations, we can help guide the investment team in their decision making, deriving value for the management team and shareholders.

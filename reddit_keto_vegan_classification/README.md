#GA DSI15 Project 3: Web APIs & Classification

---

### Overview
The aim of this project is to provide our nutrition based data analytics company with a high performing classifier to enhance the core product of the company. Secondly, we are also tasked to provide insights to 2 trending diets namely, vegan and keto.

---

### Problem Statement
Nutrino is a leading provider of nutrition related data services and analytics. As part of the data science team, we have been tasked to generate business insights curated from popular social media platforms. The company will be able to use that information to better understand customers & markets, enhance decision-making, and ultimately increase profitability.

To do so, we will first be scrapping data from reddit and using classification models such as Logistic Regression and Naive Bayes to uncover patterns within 2 popular diets, Keto and Vegan. We will measure our success using several classification metrics including accuracy and F1 score.

We hope to reveal previously unrecognised sub-trends that pertains to attitudes, lifestyles and buying behaviour, strong sub trends as opposed to passing sub trends. With a better understanding of the population and their eating patterns, our clients will be able to strengthen their targeted marketing campaigns and improve on the success of their products and campaigns.

---

### Executive Summary
As the data science team in Nutrino, we have been tasked to build a classifier to improve core product of the company, which is to provide nutrition related data services and analytics. We are also tasked to identify patterns on 2 currently trending diets, keto and vegan.

Our classifier was successful in predicting at an above 90% accuracy score. We also identified patterns in the motivations and preferences of the 2 groups of subredditors, which will help determine the kind of customer engagement with teach group.

---

### Notebooks:
- [Data Scrapping and Cleaning](./book1_data_scrapping_cleaning.ipynb)
- [EDA](./book2_eda.ipynb)
- [Modeling and Recommendations](./book3_preprocesing_modeling_recommendations.ipynb)


---

### Learning Objectives
- Adopt thorough documentation best practices
- Scrap, clean and preprocess data
- Describe my data with the written language as well as data visualisations
- Identify patterns and trends, using code and statistical knowledge
- Preprocess and use models to make predictions
- Translate findings into recommendations
- Convey the key message to a semi-technical audience

---

#### Deliverables
For this project, there will be 3 components:
- 3 x Jupyter notebooks that contains the codes and analysis commentary of the process.
- This README file that provides an introduction to and overview of your project.
- 1 x Presentation slides in pdf format

You can find these here: https://git.generalassemb.ly/kennylimyx/projects/tree/master/project_3

---

### Datasets
3 datasets in separate csv-files were saved, containing:
- keto_clean.csv that contains clean text data and label from the vegan subreddit, before dropping null and duplicates
- vegan_clean_2.csv that contains clean text data and label from the keto subreddit, before dropping null and duplicates
- data_clean.csv that contains all relevant data of posts from both subreddits, after dropping null and duplicates

---

### Data Description
Vegan subreddit: https://www.reddit.com/r/vegan/
Keto subreddit: https://www.reddit.com/r/keto/


---
### Conclusions and Recommendations
There were 2 keys questions that we set out to answer in our problem statement:
1. Can we build a classifier, with at least 90% accuracy, to sort text data from Keto and Vegan subreddits?
2. Can we draw insights from these text data for targeted marketing?

After data cleaning, feature engineering and EDA, we ran our text data through a couple of vectorizer-model combinations. We tuned the hyperparameters to generate the best scores. From there, we scored them on the training data, using the accuracy scores. We chose the model with the highest accuracy score and scored our optimal model with the test data. Finally, our classifier achieved a test score of 0.996, which means that it correctly classified text data 99.6% of the time.

We also drew insights from the EDA and profiled our target market. We realised differences in motivations and preferences between the 2 groups. Our recommendations are tailored to each group with a focus on educating for the vegans and building a strong community for the keto crowd.

With these, we will be able to provide better insights to our clients to help with their marketing campaigns.

Our recommendations are:
- further develop the classifier to continuously improve our core product of generating data analytics
With the high accuracy of our proof of concept, we can invest further resources to develop the model to eventually classify all available data, to contribute to our core product of nutrition data related services.   


- vegan insights: focus on educating the target market
With vegan subredditors, we noticed that the users were highly discerning. Afterall, vegans have made a life changing commitment to the lifestlye to avoid meat and animal products. They are concerned with making the world a better place. In order to rally these users, frequently post about the science behind veganism, share insights on how they can contribute to reduce animal cruelty and keep them updated on the change that veganism is bringing.


- keto insights: focus on building a strong community
With keto subredditors, a common goal/motivation is weight loss. Build a community with these people, share progress, recipes and tips. Build a platform when people can freely share their thoughts and concerns.

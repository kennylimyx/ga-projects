#GA DSI15 Project 1: Increase SAT Participation Rates!

---

### Overview
This is our first ever project as batch 15 of the Data Science Initiative in GA.
Currently in week 2, we have touched on Basic Python, Basic Statistics, Pandas and Data Visualisations.

The aim of this project is to provide the SAT Management with recommendations to improve the participation rates. I will be basing my recommendations on SAT and ACT data from 2017 & 2018, as well as some third party research.

---

### Problem Statement
We have seen over the years that ACT (a competitor) gain considerable market share in the US, with almost 35% of the states reporting 100% participation rates in graduating high school seniors. The College Board, administrator of the SAT, wishes to increase participation rates to allow SAT to return to its status as the unanimous choice of exit exam.

---

### Executive Summary
Brought in as a consultant to help the SAT increase participation rates in the United States. In the last 2 years we observed some traction with the SAT. I aim to analyse the SAT/ACT data from 2017 to 2018 to generate actionable insights for the organisation to keep the momentum going and further increase participation rates.

### Contents:
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

---

### Learning Objectives
- Adopt thorough documentation best practices
- Describe my data with the written language as well as data visualisations
- Identify patterns and trends to generate insights, using code and statistical knowledge
- Convey the key message to a non-technical audience

---

#### Deliverables
For this project, there will be 3 components:
- 1 x Jupyter notebook that describes my data with visualisations & statistical analysis.
- This README file that provides an introduction to and overview of your project.
- 1 x Presentation slides in pdf format

You can find these here: https://git.generalassemb.ly/kennylimyx/projects/tree/master/project_1

---

### Datasets
Four datasets in separate csv-files were used, containing:
- SAT Scores 2017
- ACT Scores 2017
- SAT Scores 2018
- ACT Scores 2018

The datasets individually contain participation rates and test scores for each of the 50 states in the United States for the respective years.

You can see the source for the data here:
SAT data [here](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/)
ACT data [here](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows)

---

#### Additional Data
Links to other 3rd party research will be included here:
https://www.testive.com/illinois/
https://www.testive.com/state-sat-act/
https://www.testive.com/colorado-sat-change-2017/
https://www.investopedia.com/articles/markets/080116/americas-poorest-states-2016.asp
https://www.hanoverresearch.com/media/Best-Practices-to-Increase-SAT-Participation-1.pdf

---

### Data Dictionary

SAT Scores 2017/2018

| Feature | Type | Dataset | Example | Description |
| --- | --- | --- | --- | --- |
| **state** | *object*| SAT | Alabama | This indicates the state in which the participants were from. |
| **sat_participation_pct_2017** | *float* | SAT | 0.05 | The percentage of cohort eligible in the state that participated in the SAT (the value shown is a fraction. This means 0.05 is intepreted as 5%). |
| **sat_reading_writing_2017** | *integer* | SAT | 593 | The score is scaled from the sum of the raw scores of the Reading as well as the Writing and Language Test. |
| **sat_math_2017** | *integer* | SAT | 572 | The score is scaled from the sum of the raw scores of the Math (non - calculator) as well as the Math (Calculator) Test. |
| **sat_total_2017** | *integer* | SAT | 1165 | This is a sum of the scaled scores of the 2 test scores above. |


ACT Scores 2017/2018

| Feature | Type | Dataset | Example | Description |
| --- | --- | --- | --- | --- |
| **state** | *object* | SAT | Alabama | This indicates the state in which the participants were from. |
| **act_participation_pct_2017** | *float* | SAT | 1.00 | The percentage of cohort eligible in the state that participated in the SAT (the value shown is a fraction. This means 1.00 is interpreted as 100%). |
| **act_english_2017** | *float* | SAT | 18.9 | Each individual test of the ACT is scored on a scale of 1–36. The higher the score, the better. |
| **act_math_2017** | *float* | SAT | 18.4 | Each individual test of the ACT is scored on a scale of 1–36. The higher the score, the better. |
| **act_reading_2017** | *float* | SAT | 19.7 | Each individual test of the ACT is scored on a scale of 1–36. The higher the score, the better.|
| **act_science_2017** | *float* | SAT | 19.4 | Each individual test of the ACT is scored on a scale of 1–36. The higher the score, the better. |
| **act_composite_2017** | *float* | SAT | 19.2 | The composite score is calculated by taking the average of the 4 tests and rounding it up or down accordingly (If the average score is more than 0.5, it is rounded up) |

---

### Conclusions and Recommendations
I recommend for the College Board to increase participation by:
- Approaching local governments to mandate SAT testing for all high school juniors
- providing fee waivers for SAT Testing

I also recommend for the college board to focus their efforts on West Virginia.
West Virgina is the poorest state in the USA as of 2018, according to Investopedia. At the same time, it is not an ACT mandated state and has a low SAT participation rate.

Since forking out test fees are a concern for high achieving yet low income students, it is possible to increase the participation rates.

# Phase_3_project
<img width="1200" height="800" alt="image" src="https://github.com/user-attachments/assets/f329987c-2520-4d2b-884f-1537d2637e78" />
## Project overview

H1N1 has a significant history marked by two major pandemics: the 1918 influenza pandemic and the 2009 H1N1 pandemic, both of which had profound impacts on global public health. The 2019 H1N1 pandemic, also referred to as "swine flu," caused high infections during the summer in the Northern Hemisphere and increased activity during the cooler seasons. Its unique characteristic is the high rates of infection and death among a relatively young population, unlike the seasonal flu, which affects the elderly more.

The H1N1 and seasonal flu vaccination dataset collects behavioral, health, and demographic information of individuals to understand vaccination patterns and predict who is likely to get vaccinated. The insights can guide public health campaigns, policy-making, planning, and development of strategic response measures, and resource mobilisation

The aim of this study is to predict how likely individuals are to receive their H1N1 flu vaccine. I believe the prediction outputs (model and analysis) of this study will give public health professionals and policy-makers, as an end user, a clear understanding of factors associated with low vaccination rates. This in turn, enables end users to systematically act on those features hindering people to get vaccinated.

---

## Business and Data understanding

This data comes from United States National Center for Health Statistics: The National Flu Survey from 2009, which inquires about whether or not people received the seasonal flu and/or the H1N1 flu vaccination, as well as their demographic, behavioral, and health factors. There are 26,707 respondents to this survey. In this project i chose H1N1 vaccination rate as my target variable. I used all features in the survey and filled missing values using the Scikit sklearn SimpleImputer.

The most influential factors determining vaccination status are found to be health-related factors(Doctor Recommendation of H1N1 vaccine, Health Insurance, Opinion of H1N1 Vaccine Effectiveness, and Opinion of H1N1 Risk). Demographic and behavioral factors do have some correlation to the H1N1 vaccination but not as strong as the health_related factors.

---

## Modelling
To determine and evaluate logistic regression model, I model two logistic regression where one is a baseline model and the other one is improved model of the baseline. The class balance problems, poor recall and precision metrics are address to reflect a more realistic predictive model

---

## Evaluation
I evaluated my model using:-
  1. Accuracy score
  2. Recall
  3. Precision
  4. F1 score
  5. ROC_Curve and AUC

---

## Conclusions
The public health stakeholders should encourage medical professionals to recommend vaccines to the patients. More public health campaigns and outreach on the vaccine should be emphasized to boost confidence among the patients and reduce risk-based perception of the H1N1 vaccine.

---
## Repository

Data:
- https://www.drivendata.org/competitions/66/flu-shot-learning/data/

Notebook:
- https://github.com/ronohcollins/Phase_3_project/blob/main/P3_Project.ipynb

Presentation:
- https://github.com/ronohcollins/Phase_3_project/blob/main/Phase_3_project%20presentation.pptx



# Diabetes-Prediction-with-ML

###### Description
###### As part of the Capstone group project for Samsung Innovation Campus, we developed a Machine Learning model that predicted diabetes  

## Overview
As part of the Samsung Innovation Campus, my team and I built a Machine Learning Model that analyzed whether a person had diabetes or not, with an accuracy of 87%.

## Objective
Diabetes is a condition that affects over 400 million people across the world. Despite there being extensive research in the field, there is no known cure for it yet. Our project aims to develop a machine leanring model that can predict, based on lifestyle questions and health parameters whether a person has diabetes or not, with high level accuracy. We hope that this technology can contribute to the accessibility of diabetes detection and management tools, which can contribute to early detection and amangement of diabetes.

## Tools Implemented
1. Python - Programming Language for Analysis
2. Pandas Library - Dataframe management
3. Numpy Library - Numerical analysis of dataset
4. MatPlotLib Library - Visualizing features' correlation to diabetes
5. Seaborn - Visualiing  features' correlation to diabetes as heatmaps
6. SciKitLearn - Model Training and Testing
7. Lazy Predict - Analyzing most effective regression model for diabetes
8. Jupyter Notebook - Interactive Coding Platform

## Data
The original dataset comprised of three files. 
The first file had all cases classified as Non-Diabetic (0), Pre-Diabetic (1) or Diabetic (2) cases. 
The second file had a balanced, binary data set where all cases were classified as Non-Diabetic (0) or Diabetic (1). 
The third file had an unbalanced binary data set where all cases were classified as Non-Diabetic (0) or Diabetic (1).

The dataset was pre-processed to remove any null/out-of-bound values. It consisted of 253,680 survey responses and 21 feature variables. The files included the following key features:
### Health Parameters:
- HighBP: Does the individual have High BP?
- HighChol: Does the individual have High Cholesterol?
- HeartDiseaseorAttack: Does the individual have a history of heart conditions?
- Stroke: Does the individual have a history of stroke?
- BMI: The individuals BMI range?

### Lifestyle Choices:
- MentHealth: Does the individual have any history of mental health conditions?
- PhysActivity: Has the individual exercised over the part 30 days (not including job)?
- Smoker: Has the individual consumed over 100 cigarettes (5 packets)?
- HvyAlcoholConsump: Does the individual consume alcohol regularly (more than 14 drinks a week for adult men and more than 7 drinks a week for women)?
- Fruits/Veggies Consumption: Does the individual consume fruits and veggies with at least one meal day?

### Additional Questions:
- Income: What is the category of 'range of income' does the individual come under?
- Age: What is the category of 'range of age' of the individual?
- Sex: What is the gender of the individual?
- AnyHealthcare: Does the indivdual have any healthcare plan/insurance?
- NoDocbcCost: Was the individual not able to access any healthcare services, despite their need for it, due to financial reasons over the past year?


The cleaned dataset was sourced from Kaggle.
[Link: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset/data]

## Accomplishments:
- Analyzed the various factors that positively and negatively influence the likelihood of developing diabetes.
- Implemented the Lazy Predict library to analyze the top three machine learning models that are most efficient for diabetes prediction
- Developed, trained and tested a LightGB Machine Learning Model for diabetes prediction with 86% accuracy.
- Developed, trained and tested a Logistic Regression Machine Learning Model for diabetes with 85% accuracy.
- Made use of libraries and tool kits to automate processes and save on time.


## Future Goals
- Since our model is handling clinical data, our first goal is to train the model on preprocessed datasets from Kaggle, or machine learning repositories. 
- Implement a user interface, in the form of a website to deploy the ML model in the back end. 
- Take input such as lifestyle and medical parameters from the user and give real time predictions.



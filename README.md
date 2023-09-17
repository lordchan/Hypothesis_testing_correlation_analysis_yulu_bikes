# Hypothesis testing and correlation analysis on the demand of yulu bikes

## Introduction
This repository contains the implementation of the Yulu Analysis Project, aimed at understanding the factors affecting the demand for shared electric cycles in the Indian market. The project was conducted to help Yulu, India's leading micro-mobility service provider, gain insights into variables that significantly predict the demand for their shared electric cycles.

## Project Implementation
Dataset [https://github.com/lordchan/Hypothesis_testing_correlation_analysis_yulu_bikes/blob/main/yulu_dataset.txt]
The dataset used for this analysis can be found here. It includes the following columns:

datetime: Date and time
season: Season (1: spring, 2: summer, 3: fall, 4: winter)
holiday: Whether the day is a holiday (0: No, 1: Yes)
workingday: Whether the day is a working day (0: No, 1: Yes)
weather: Weather conditions (1: Clear, 2: Mist, 3: Light Snow, 4: Heavy Rain)
temp: Temperature in Celsius
atemp: Feeling temperature in Celsius
humidity: Humidity
windspeed: Wind speed
casual: Count of casual users
registered: Count of registered users
count: Count of total rental bikes (casual + registered)
Implementation Steps
To perform the analysis and answer the project's questions, the following steps were taken:

## 1. Data Import and Exploration
The dataset was imported into a Jupyter Notebook using Python's Pandas library.
The structure and characteristics of the dataset were examined.
Categorical attributes were converted to the 'category' data type if necessary.
Missing values were detected and handled.
A statistical summary of the dataset was generated.
## 2. Univariate Analysis
Distribution plots of continuous variables were created.
Bar plots and count plots of categorical variables were generated.
## 3. Bivariate Analysis
Relationships between important variables were explored:

The relationship between working day and the count of rented electric cycles.
The relationship between season and the count of rented electric cycles.
The relationship between weather conditions and the count of rented electric cycles.
Insights were illustrated based on the exploratory data analysis (EDA).

## 4. Hypothesis Testing
2-Sample T-Test was used to check if working day has an effect on the number of electric cycles rented.

ANOVA was conducted to check if the number of cycles rented is similar or different in different weather conditions and seasons.

Chi-square test was performed to check if weather conditions are dependent on the season.

Null hypotheses (H0) and alternate hypotheses (H1) were defined for each test.

Assumptions of the tests were checked, including normality and equal variance.

## 5. Inference
Based on the p-values obtained from the tests, decisions to accept or reject null hypotheses were made.
Conclusions and insights were drawn from the analysis, providing valuable information to Yulu regarding factors affecting the demand for shared electric cycles in the Indian market.
## Notebook Quality
The Jupyter Notebook used for this analysis is well-structured with clear explanations, comments, and visualizations.
The code is thoroughly commented for clarity.
Best practices for hypothesis testing were followed, and conclusions are supported by the data.
Evaluation Criteria
The project was evaluated based on defined criteria, including problem statement definition, data exploration, hypothesis testing, and overall notebook quality.
## Conclusion
This project aimed to provide Yulu with valuable insights into the factors influencing the demand for shared electric cycles in the Indian market. The implementation involved thorough data exploration, hypothesis testing, and clear documentation. The results and analysis findings can be found in the Jupyter Notebook included in this repository.

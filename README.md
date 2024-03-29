# Bellabeat Case Study: Using Fitbit Fitness Tracker
This repository contains an analysis of Fitbit Fitness Tracker data as part of a Bellabeat case study. The purpose of this analysis was to gain insights into how consumers are using the Fitbit app and discover trends and insights for Bellabeat's marketing strategy.

## Business Task
Bellabeat is a successful small wellness technology company that has the potential to become a larger player in the global smart device market. Bellabeat's cofounder and Chief Creative Officer, Urška Sršen, believes that analyzing smart device fitness data could help unlock new growth opportunities for the company. The business task for this analysis is to answer the following questions:

1)  What are some trends in smart device usage?
2) How could these trends apply to Bellabeat customers?
3) How could these trends help influence Bellabeat's marketing strategy?

## Data
The data used in this analysis was generated by respondents to a distributed survey via Amazon Mechanical Turk between 03.12.2016-05.12.2016. Thirty eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. The data is publicly available on Kaggle here.

## Analysis
The analysis of the data revealed several trends in smart device usage. The average usage of the app is high, with users on average using the app for 20 hours or 1218 minutes. However, the numbers of usage in each mode suggests that people who use the app do not use it for sport purposes.

The biggest slice of usage time goes to sedentary mode (81%), while very active minutes only make up 1.7% of the total usage time. Additionally, users tend to use the app more during weekdays than on weekends. Increasing the usage of the app by users doesn't necessarily increase the calories burned, since users primarily use the app in sedentary mode.

## Recommendations
Based on these findings, Bellabeat could make the following recommendations for their marketing strategy:

1. Encourage users to use the app on weekends.
2. Encourage users to burn more calories by increasing their activity to achieve levels in the app, which could give them benefits and promotions.
3. Build a personal program for users to encourage them to be more active.
4. Connect to other applications for promotions.

## Files
README.md: this file.
Bellabeat_Case_Study_Fitbit_Analysis.ipynb: Jupyter notebook containing the data analysis.
Bellabeat_Case_Study_Fitbit_Analysis.html: HTML version of the Jupyter notebook.
fitbit.csv: the dataset used in the analysis.

## Dependencies
The following Python packages were used in this analysis:

- pandas
- numpy
- matplotlib
- seaborn
- datetime
- textblob

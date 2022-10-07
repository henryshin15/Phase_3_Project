### Phase_3_Project

# Predicting vaccine status based on 2009 H1N1 survey data

This project is a part of a [DrivenData](https://www.drivendata.org/competitions/66/flu-shot-learning/page/210/) competition.  

## Project Intro/Objective
The purpose of this project is to predict whether people got the H1N1 vaccine using information that they shared about their backgrounds, opinions, and health behaviors. The stakeholder was chosen as the CDC so that their will be better preperation for the next COVID-19 scale pandemic by targeting unvaccinated people based on the findings of the project. The overall goal of increasing the vaccination rate is to promote a healthier society by achieving herd immunity. 

![Picture of CDC branch](https://cloudfront-us-east-2.images.arcpublishing.com/reuters/TK4VUHBKIFJYDGOIDG76KJZUYM.jpg)

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling

### Technologies
* Python
* Pandas, jupyter, Scikit-learn, Matplotlib

## Project Description
Our project's main objective was to answer the following questions for the stakeholder:
* Could H1N1 vaccination status be predicted using survey data?
* What factors increase or decrease a person's liklihood of being vaccinated?
* What steps could be taken to increase vaccine uptake in a future pandemic?

The COVID-19 pandemic saw large-scale loss of life, with over one million deaths in the USA alone and the number continuing to rise. The number one tool to defend against COVID-19 and any future pandemics is widespread vaccination. However, two years after vaccines began to roll out in the USA, the [fully vaccinated population is only 68%.](https://covid.cdc.gov/covid-data-tracker/#vaccinations_vacc-people-additional-dose-totalpop) The CDC Vaccine Task Force is seeking insights into determining which people would need vaccine messaging, and what ways would be best to get them to vaccinate.

## Bottom Line
Our best predictive model was 90% precise, meaning it correctly identified 9 out of 10 people who were unvaccinated and would benefit from vaccine outreach. We found that the biggest factor used to predict a person's vaccination status was whether or not their doctor had recommended the vaccine, meaning we need to increase both physician participation in recommending a future vaccine as well as increasing access to physicians. 

Other recommendations we made from our findings are that a public virus education campaign could increase vaccinations as more knowledgeable people are more likely to be vaccinated. We also identified some minor demographic features such as region of the USA that had some impact on a peron's vaccination status which could be used to potentially target undervaccinated groups.

## Data Overview
The dataset contained around 27,000 data points collected by a phone survey during the 2009 H1N1 pandemic. We found that the vaccination rate for this pandemic was 20%.

The data set contained some challenges that we needed to overcome. Due to the survey nature of the data collection, large portions of the data were missing or incomplete. We relied on imputation and feature pruning to help clean the data for our modeling. To help combat this, we also designed a secondary model that took in only the demographic features that would be easy to obtain without performing a costly survey.


## Getting Started
In order to get the dataset needed, you need to sign up for the [competition](https://www.drivendata.org/competitions/66/flu-shot-learning/data/) hosted by Driven Data.

## Featured Notebooks and Presentation
* [Notebook](https://github.com/Patrick-Arnold/Phase_3_Project/blob/main/Main_Notebook.ipynb)
* [Presentation](https://github.com/Patrick-Arnold/Phase_3_Project/blob/main/Presentation.pdf)

## Contributing Project Members
|Name     |  Github Handle   | 
|---------|-----------------|
|Patrick Arnold|(https://github.com/Patrick-Arnold)|
|Henry Shin |(https://github.com/henryshin15)|

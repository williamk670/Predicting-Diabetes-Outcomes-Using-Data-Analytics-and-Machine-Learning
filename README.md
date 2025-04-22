# Predicting-Diabetes-Outcomes-Using-Data-Analytics-and-Machine-Learning
Research project on predicting diabetes outcomes in the Pima Indian population using data analytics and machine learning models in R, including an interactive Shiny app.

# Predicting Diabetes Outcomes Using Data Analytics and Machine Learning

## Overview

This research project explores the relationship between medical and demographic variables and their predictive power in diagnosing diabetes, focusing on the Pima Indian population. Using data analytics and various machine learning models in R, we identify the strongest predictors and evaluate model performance. An interactive Shiny app was developed for real-time diabetes prediction.

## Research Question

**How do medical and demographic factors impact diabetes prediction, and which machine learning model provides the most accurate classification?**

## Dataset

- **Source:** Pima Indians Diabetes Dataset  
- **Origin:** National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK) via Kaggle  
- **Samples:** 768  
- **Variables:** 8 predictors + 1 target  
- **Target Variable:** Diabetes diagnosis (1 = Diabetes, 0 = No Diabetes)

## Methods

- **Data Analysis & Visualization:** `ggplot2`, `corrplot`, `dplyr`
- **Machine Learning Models:**  
  - Logistic Regression  
  - Random Forest  
  - Neural Network  
  - Naive Bayes  
- **Interactive Tool:** Developed a Shiny app for real-time diabetes prediction

## Key Findings

- **Top Predictors:** Glucose, BMI, Age
- **Model Accuracy:**
  - Logistic Regression: 77%
  - Random Forest: 77%
  - Naive Bayes: 76%
  - Neural Network: 73%
- Blood Pressure, Skin Thickness, and Insulin had weaker predictive power due to inconsistencies in the dataset.

## Future Work

- Refine data preprocessing and handling of missing values
- Experiment with additional machine learning models
- Enhance Shiny app usability and deployment

## Acknowledgements

This project was supported by:
- Data Science, Analytics, and Visualization Program
- Professor Mariah Yelenick  
- Dr. Amber Camp  
- Dr. Rylan Chong  

Funded in part by NSF under grant numbers HRD-2217242 (INCLUDES Alliance ALL SPICE) and PEARL DUE-2030654 (S-STEM). The content is solely the responsibility of the authors and does not necessarily represent the official views of NSF.

## Reference

World Health Organization. (2023). *Diabetes*. https://www.who.int/news-room/fact-sheets/detail/diabetes

## Contact

- **Email:** wkim151416@gmail.com  
- **Phone:** +1 (808) 206-1708  
- **GitHub:** [williamk670](https://github.com/williamk670)

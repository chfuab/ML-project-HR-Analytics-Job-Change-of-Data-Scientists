# ML-project-HR-Analytics-Job-Change-of-Data-Scientists

## Background
A company wants to hire data scientists among people who have passed some courses conducted by the company. The company wants to know which of these candidates are really wants to work for the company after training or looking for a new employment. With the demographics, education, experience etc. data during candidates' signup and enrollment, a dataset is designed to understand factors leading to whether a candidate will work for the company or looking for new jobs.

## Aim of the project
This project aims at selecting the machine learning models and model parameters with the best performance in predicting whether a candidate will look for new employment or not.

## Content of the project
### Data preprocessing
  Filling missing values by mode <br />
  Drop columns useless for data analysis <br />
  Binning the experience columns <br />
  Data cleaning <br />
### Exploratory data analysis
The data is imbalance, the number of candidate working for the company is more than 3 times to those looking for new employment. <br />
Upsampling will be performed and effect of different upsampling techniques are to be compared <br />
![imbalance](https://github.com/chfuab/ML-project-HR-Analytics-Job-Change-of-Data-Scientists/blob/main/image/imbalance_data.png) <br />
### Comparing performance of different machine learning models
Performance (without upsampling) of kNN, Naive Bayes classifier, Decision tree as well as RandomForest are evaluated. RandomForest gives the best overall performance. <br />
![Random Forest Performance](https://github.com/chfuab/ML-project-HR-Analytics-Job-Change-of-Data-Scientists/blob/main/image/Random%20Forest_Performance.png)
### Effect of upsampling techniques
SMOTENC, SMOTEENN and Resampling are compared. Resampling gives the best performance <br />
![resampling](https://github.com/chfuab/ML-project-HR-Analytics-Job-Change-of-Data-Scientists/blob/main/image/Random%20Forest%20with%20Resampling.png)
### Hyperparameters optimization
Random search for optimized parameters is performed 
![Hyperparameters optimization](https://github.com/chfuab/ML-project-HR-Analytics-Job-Change-of-Data-Scientists/blob/main/image/Hyperparameters_optimization.png)


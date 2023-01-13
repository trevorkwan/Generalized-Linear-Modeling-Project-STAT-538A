# Generalized Linear Modeling Project (STAT 538A)

**Investigating factors that influence the income of the citizens in US**

## Introduction

### Background

Identifying the factors that influence people's income is crucial for a fair society. The "Adult Data Set"[5] is such a dataset that records people's income and related variables in the US. It was collected by Barry Becker from the 1994 Census database. It allows us to predict whether income exceeds \$50K/year based on adult census data. With this dataset, we explore how the recorded variables influence people's income.

### Related Works

The UCI adult data was first cited by [1]. This work mainly focuses on the machine learning methodologies, it compares the prediction accuracy of several basic machine learning models. The prediction accuracy of the adult dataset reported in [1] is around 85%. [2] is a more recent work that also focuses on the prediction task. It proposes a gradient boosting approach which brings the accuracy to 88%. The dataset is also very popular in the machine learning fairness literature. [3] compares it's proposed model and some baseline methods in terms of prediction accuracy and discrimination scores. [4] extends this dataset into a more suitable dataset for fair machine learning. 


###  Our reseach objectives

In this project, by utilizing the learned generalized linear models (GLM), we want to mainly focus on the following two tasks:
* Build a GLM prediction model which will perform well in the dataset;
* Identify some key variables (or variable combinations) which have a large influence on one's income.

See the full report [here](https://github.com/trevorkwan/Generalized-Linear-Modeling-Project-STAT-538A/blob/main/final_report.ipynb).

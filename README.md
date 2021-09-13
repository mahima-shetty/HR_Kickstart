<!-- ![image](https://user-images.githubusercontent.com/41589522/133105285-88274864-aeae-438b-9266-259d7cdebfc8.jpg) -->

<!-- https://img.shields.io/badge/Made%20with-Scikit--Learn-orange -->

# HR_Kickstart

## HR_KickStart is a web based application made with affection :innocent: for budding HR trainee & enthusiasts.
https://hr-kickstart-mahimasshetty.herokuapp.com/

Template Website created with Mashup Template/Unsplash

# HR_KickStart
![image](https://user-images.githubusercontent.com/41589522/133105297-993ea492-2ee8-474b-a714-9d0a6ba49fac.jpg)


### Organizations suffer a lot of man power loss. The reasons may be plenty if we brainstorm on this. But in terms of data, we have handsome number of characteristics which can determine whether the employee will stay or leave the organization

These are the top reasons employees decide to quit their jobs:
- Needing more of a challenge.
- Looking for a higher salary.
- Feeling uninspired.
- Wanting to feel valued.
- Seeking a better management relationship.
- Searching for job growth and career advancement.
- Needing more feedback or structure.
- Wanting a different work environment.

***Credit: Indeed Website https://www.indeed.com/career-advice/career-development/reasons-employees-leave***

In our dataset, we have good characteristics like 

**Satisfaction level** </br>
Satisfaction level plays an important role in contributing towards the model making decision. Also Satisfaction level is an important aspect for an employee to stay in the organization.  

**Last evaluation score**
Last Evaluation score is great measure to know whether an employee is really active in his work or not. Even it was good attribute for making decision in model making, as this attribute had good correlation with respect to other attributes.

**Estimated number of projects** 
An employee and his team take in a project or so for his respective role and they start developing. In certain case, if an employee entire tenure if he didn't get good number of projects to work on, he may shift to different place or organization to work with expecting good number of projects to work oon.

**Monthly average hours etc.**
Even it makes a good metric for model also. Monthly average hours can be estimated if the person is fatigued by overworking, or he is feeling uninspired towards work. If he takes leave or vacation or some reason, it will lessen the monthly average hours and can impact the decision model.

**Salary (range) given to the employee**
Salary given to the employee also matters in formation of model making decision.

**Work Accident**
If the employee had faced some work accident in his tenure, it may affect the working experience for that employee as well.

**Promotion in 5 years**
Within 5 years, if an employee didn't receive any promotion for his work, it may reduce the experience of the employee working in that organization. 

This can be used to determine whether the employee will stay or not.

# ML Model Making
The encoded variables
**One Hot Encoding - the categorical feature is not ordinal**

**Label Encoding - the categorical feature is ordinal (like the Salary, Yes/No above)**

oversampling/undersampling techniques if the dataset was highly imbalanced. You can also specify the various ways in which you tackled data leakages, overfitting, bias-variance tradeoffs, and improved your accuracy while using the learning curves.

**Feature Scaling – Standardization and Normalization**
To reduce number of outliers in the data, the data should be standardized and normalized.
Normalization typically means rescales the values into a range of [0,1]. Standardization typically means rescales data to have a mean of 0 and a standard deviation of 1 (unit variance).

Normalization typically means rescales the values into a range of [0,1]. Standardization typically means rescales data to have a mean of 0 and a standard deviation of 1 (unit variance).

**Why Random Forest Classifier?**

There are many Classfication models, Logistic Regression, SVM, etc. But kind of data we are facing having variance issue, it is proven that Random Forest works best for Variance balancing. So I chose Random Forest Regressor. The random sampling technique used in selecting the optimal splitting feature lowers the correlation and hence, the variance of the regression trees. It improves the predictive capability of distinct trees in the forest.
For data model, I have used Random Forest Classifier as it was best compared with various ML models for this type of data. 

![15391random_forest_gif](https://user-images.githubusercontent.com/41589522/133066114-4e3023a7-48e4-4f7c-b764-a2a6c8b2f55d.gif)


<!-- ![Random Forest 03](https://user-images.githubusercontent.com/41589522/128638871-b6d1eba3-b5bf-4c28-b9a5-af7c8d36669d.gif) -->
***Image Credit: Analytics Vidhya***
<hr>

## Scores in Final Model 😀



 Precision is the ratio of correctly predicted positive observations to the total predicted positive observations.
 Recall (Sensitivity) - Recall is the ratio of correctly predicted positive observations to the all observations in actual class - yes.
 F1 score - F1 Score is the weighted average of Precision and Recall. Therefore, this score takes both false positives and false negatives into account.
 F1 Score = 2*(Recall * Precision) / (Recall + Precision)
 
 
***precision_score: 0.8717948717948718***

***recall_score: 0.6631989596879063***

***f1_score: 0.7533234859675036*** 


<hr>

## Model Done! Integration with website 😇

Testing Prediction Model |  Content Page for HR enthusiasts
:-------------------------:|:-------------------------:
![ezgif com-gif-maker](https://user-images.githubusercontent.com/41589522/128636277-1efa5c6c-f887-48d4-b155-9e12c5aefec1.gif)  |  ![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/41589522/128636415-46886f34-bce1-49b9-a67e-f5236bdc7b28.gif)
<!-- 
![ezgif com-gif-maker](https://user-images.githubusercontent.com/41589522/128636277-1efa5c6c-f887-48d4-b155-9e12c5aefec1.gif)  |   ![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/41589522/128636415-46886f34-bce1-49b9-a67e-f5236bdc7b28.gif)
 -->

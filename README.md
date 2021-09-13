<!-- ![image](https://user-images.githubusercontent.com/41589522/133105285-88274864-aeae-438b-9266-259d7cdebfc8.jpg) -->
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
- Satisfaction level 
- Last evaluation score 
- Estimated number of projects 
- Monthly average hours etc.
- Salary range given to the employee

This can be used to determine whether the employee will stay or not.

# ML Model Making

oversampling/undersampling techniques if the dataset was highly imbalanced. You can also specify the various ways in which you tackled data leakages, overfitting, bias-variance tradeoffs, and improved your accuracy while using the learning curves.

Feature Scaling – Standardization and Normalization
The encoded variables – One Hot Encoding, Label Encoding
The Feature Reduction techniques used
Feature engineering that was performed

GridSearchCV or RandomizedSearchCV

For data model, I have used Random Forest Classifier as it was best compared with various ML models for this type of data. 

![15391random_forest_gif](https://user-images.githubusercontent.com/41589522/133066114-4e3023a7-48e4-4f7c-b764-a2a6c8b2f55d.gif)


<!-- ![Random Forest 03](https://user-images.githubusercontent.com/41589522/128638871-b6d1eba3-b5bf-4c28-b9a5-af7c8d36669d.gif) -->
***Image Credit: Analytics Vidhya***
<hr>

## Scores in Final Model 😀

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

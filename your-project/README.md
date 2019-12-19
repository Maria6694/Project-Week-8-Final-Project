<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Prediction of car-crashes: Insurance company
*[Maria Platas]*

*[October 2019, Ironhack Barcelona]*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-questions)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
Every year, we hear the news saying there are many accidents and insurance companies are the ones covering driver's back. Therefore, insurance companies needed a way to predict if a client was more probable to have an accident to avoid losing profits.
That is why these type of companies are really data-driven and need these models that help them classify their clients on whether they will have an accident or not.

In this project I want to create an algorithm that predicts whether a person will have an accident or not. In order to do that, I will be using a dataset from Kaggle of an insurance company from the USA, data is from 2018.

To predict if a client will have an accident or not, I will use supervised learning algorithms.

## Hypotheses / Questions

In this project I would like to predict if one customer is going to have an accident or not. Therefore I will create a Machine Learning Model that will be able to predict if one person will have a car crash. It would be an approximation of real model an  insurance company would be able to use.

## Dataset
The dataset is public and contains the data from clients of an insurance company. The dataset has 10,000 rows, each of them is a client and there is the information about the characteristics of the clients. Some examples of the features are Gender, Education Level, type of insurance, type of insurance used and size of cars. The data that I will use in the project is categorical.

## Cleaning
First of all, I explored the dataset, checked and changed the name of the columns to make them more explanatory. Afterwards I dropped columns that I did not use in the analysis. The dataset was pretty clean, so I did not have to clean null values, I checked for outliers and I finally saved the clean data into the Clean Data file.

## Analysis
My analysis consisted on watching what features had an impact on making a person had an accident. 

## Model Training and Evaluation
The first part was choosing the algorithm that I was going to apply, I decided to use several algorithms and choose the one with higher accuracy and F1_score. I split the inputs and outputs into a 80% train and 20% test, so that I could check whether my predictions were good or not. As explained before, I evaluated the algorithms with accuracy, F1_Score and confusion matrix.
At the end, after testing several algorithms such as SVC, Linear SVC, Decision Tree Classifier and K-nearest neighbours, the algorithm that predicts better is k-nearest neighbours with n = 6, with Eucledian distance and with PCA. I achieved a stable model with 0.76 accuracy and 0.71 F1_Score.

## Conclusion
In this project I have created an algorithm that, with 0.76 accuracy, predicts if a person is going to have an accident or not. My main challenge has been to work only with categorical data and dealing with class imbalance.

## Future Work
My aim with this project was to try to apply what we have learned to a business real case but the main limitation of this project is the following: More data. I would need more data to try to increase accuracy and F1_Score and also, I would need more features that also contribute to having an accident or not, such as the color of the car, the age of the driver or for how long did the driver had their license.
Taking into account these new variables, I would be able to reach 0.8-0.9 of accuracy and F1_Score.
I would also include data from more years and from other insurance companies to have a more complete analysis and data to feed the model.

## Workflow
First of all, the steps I followed were the following: Deciding the topic, looking for the data, exploring the data, checking for outliers and deciding what to do with them, exploratory analysis, preparation for Machine Learning, application of algorithms, checking evaluation metrics and deciding the algorithm. 
To test the accuracy of the algorithm I used the confusion matrix, F1_score and Score of the model.

## Organization
I used Trello to organize my work.

My repository has 2 folders: Code and Data.
Code you will be able to see 3 different Jupyter Notebooks with the code I used in my project. The number at the beginning indicates the order of code running. In the first Jupyter Notebook you will find the process the Data Cleaning process, in the second one, the analysis and in the last one, the application of Machine Learning and evaluation of the model.
In the folder Data it contains 2 additional Folders: Clean_data and Raw_data. In the Raw folder it is the original dataset. In the Clean_data folder you will have the cleaned dataset.

## Links
Links:


[Repository](https://github.com/Maria6694/Project-Week-8-Final-Project)  
[Slides](https://docs.google.com/presentation/d/1GXcPgX0_HxoAtqDu28mZeDD1v63ic5QBuFwtoscNCro/edit?usp=sharing)  
[Trello](https://trello.com/b/ODqgLZOU/finalproject)  

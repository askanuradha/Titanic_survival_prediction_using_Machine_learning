# Titanic survival prediction using Machine learning
<div align="center"><img src="https://github.com/askanuradha/Titanic_survival_prediction_using_Machine_learning/blob/main/RMS_Titanic_3.jpg" alt="Titanic ship" width="500"></div>

The sinking of the Titanic is one of the key sad tragedies in history and it took place on April 15th, 1912. The numbers of survivors were low due to the lack of lifeboats for all passengers. We will analyze what sorts of people were likely to survive this tragedy with the power of machine learning.
## Project Overview
The Titanic Survival Prediction project is a machine learning project aimed at predicting whether a passenger on the Titanic would have survived or not based on various features such as age, gender, class, and more. This classic dataset serves as an excellent introduction to data preprocessing, feature engineering, and predictive modeling techniques.
## Data set Attributes
The Titanic data set consists of 12 columns and 890 rows.  The dataset is divided into two parts: a training set for model development and a testing set for evaluating the model's performance. The columns are,
* PassangerID
* Survived                
* Pclass                  
* Name                     
* Sex                      
* Age                      
* SibSp
* Parch
* Ticket
* Fare
* Cabin
* Embarked
## Implementation
The project will be implemented using popular data science and machine learning libraries such as Python, Pandas, Scikit-Learn, and Seaborn. Jupyter Notebooks will be used for an interactive and collaborative development environment. 
Initially, as part of the preliminary data preprocessing stage, irrelevant columns were removed from the dataset to enhance its relevance and computational efficiency. Subsequently, a systematic approach was employed to address missing values present within the dataset. Null values within pertinent columns were imputed using the mean value of the respective column. This imputation strategy was selected in consideration of the data's characteristics and the potential impact of missing information on subsequent analytical and modeling procedures. The resulting dataset, thus refined, laid the groundwork for subsequent stages involving feature engineering, exploratory data analysis, and machine learning model development. I used a few numbers of Algorithms to train the model and predict survivability.
### Logistic Regression Algorithm
Logistic Regression is a statistical model that's particularly well-suited for binary classification problems, where the outcome variable can take on one of two possible classes. It's a type of generalized linear model that uses the logistic function to model the probability of the dependent variable belonging to one of the classes as a function of the independent variables.
### Naive Bayes Gaussian and Multinomial Algorithms
Gaussian Naive Bayes is a variant of the Naive Bayes algorithm that assumes the features within each class are normally distributed. It is suitable for continuous numeric features. Multinomial Naive Bayes is an extension of the Naive Bayes algorithm that is designed for discrete data, particularly when features represent counts or frequencies of occurrences.

# Income-prediction-with-ML-models-in-python
This project aims to classify individuals' income levels based on the UCI Adult dataset. The objective is to predict whether a person makes over $50K a year using various machine learning models. The project involves data preprocessing, exploratory data analysis, model training, and evaluation of several algorithms to determine the most effective model for this classification task.

The dataset used in this project is the UCI Adult dataset. It contains information about individuals from the 1994 Census database. The dataset is publicly available and can be downloaded from UCI Machine Learning Repository under this link: https://archive.ics.uci.edu/dataset/2/adult.
Features
* Age
* Workclass
* Education
* Marital-status
* Occupation
* Relationship
* Race
* Gender
* Capital-gain
* Capital-loss
* Hours-per-week
* Native-country
* Income (target variable)

* Models
Three machine learning models were used and compared in this project:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- 
Data Preprocessing
The preprocessing steps include:

- Converting categorical columns to category types.
- Aggregating similar categories.
- Handling missing values.
- Removing outliers.
- Splitting the data into training and testing sets.
- Applying one-hot encoding to categorical features.
- Model Training and Evaluation
Each model was trained using the training set and evaluated using the testing set. The evaluation metrics used include:

- Accuracy
- Precision
- Recall
- Specificity
- F1 Score
- AUC (Area Under the Curve)
- ROC (Receiver Operating Characteristic) Curve
- Feature Selection
- Recursive Feature Elimination with Cross-Validation (RFECV) was used to select the most important features for each model to improve their performance.

Evaluation
The models were evaluated based on multiple metrics to determine their performance:

Logistic Regression:

- Accuracy: 83%
- Recall: 55%
- AUC: 0.88
  
Random Forest Classifier:

- Accuracy: 84%
- Recall: 61%
- AUC: 0.90
- 
Gradient Boosting Classifier:

- Accuracy: 86%
- Recall: 57%
- AUC: 0.92
- 
The choice of the best model depends on the specific goal. If the primary goal is to identify the positive class accurately, Random Forest might be preferred. For overall accuracy, Gradient Boosting might be the better choice.

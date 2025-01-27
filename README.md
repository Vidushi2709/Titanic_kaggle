# Titanic - Machine Learning from Disaster 🚢

### Overview  
This project is based on the [Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) competition on Kaggle. The goal is to predict which passengers survived the Titanic shipwreck using a variety of machine learning techniques.  

Using a **Random Forest Classifier**, I achieved an **81% accuracy** on the training dataset and a **71% accuracy** on the Kaggle test dataset submissions. This project includes robust data preprocessing, feature engineering, and a machine learning pipeline.

---
### Project Objective
To predict passenger survival on the Titanic based on features such as age, gender, passenger class, and more, while applying end-to-end data preprocessing and a machine learning pipeline.
---
### How It Fits the Competition  
The Titanic competition is often considered a beginner-friendly introduction to machine learning, helping participants gain hands-on experience with:  
- Cleaning and imputing missing data.
- Encoding categorical variables.
- Engineering features for better predictions.
- Building, tuning, and evaluating machine learning models.

### Model and Pipeline
The model pipeline is built using scikit-learn, with the following components:

Preprocessing Steps:

Impute missing values for Age and Embarked.
Encode categorical features (Sex, Embarked).
Scale numerical features (Age, Fare).
Random Forest Classifier:

Hyperparameters:
n_estimators: 100
random_state: 41
Training Accuracy: 81%
Submission Accuracy: 71%
---
### Key Insights
Gender: Females had a higher survival rate than males.
Class: Passengers in 1st class were more likely to survive.
Family Size: Moderate family sizes (2–4) had better survival chances.
Fare: Higher ticket fares correlated with higher survival rates.
---
## Reference  
- Kaggle Competition: [Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)  


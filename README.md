## ABSTRACT 
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.Stroke is a cerebro-vascular ailment affecting the normal blood supply to the brain. Without proper supervision, it leads to death or long term disability. Stroke can be either ischemic or hemorrhagic. There is a possibility for the cooccurrence of both ischemic and hemorrhagic strokes. Stroke caused due to a clot in the blood vessel is known as Ischemic stroke and that due to a rupture of blood vessel is referred to as Hemorrhagic stroke. The deficiency of oxygen to the cerebral nervous system is referred to as ischemia which finally leads to their death. About 85 % of all strokes belong to ischemic category. Its frequency is accelerating in developing countries like India due to unhealthy lifestyles.

## TITLE & OBJECTIVE OF THE STUDY 
The project titled “DATA ANALYSIS ON STROKE PREDICTION” is under category “Healthcare”, which inspects the patient’s medical information performed across various hospitals. The project primarily focuses on the causes that leads to stroke, which is a binary classification done by using ML- Supervised classification algorithms and predicting. OBJECTIVE:  Determine whether the patient has a Stroke or not  Implementation of supervised ML classification Algorithms

## NEED OF THE STUDY 
29 October is observed as World Stroke Day. This day aims at spreading awareness about the fatal condition of stroke. This complication is caused due to the reduced or interrupted blood flow in the brain. This leads to insufficient nutrient and oxygen supply in the brain causing it to dysfunctional and damage. It is important to spread awareness about this condition as early detection and treatment is the only way of ensuring safe recovery and preventing fatality. In this Project, 11 clinical features like hypertension,heart disease,glucose level, BMI and so on are obtained for predicting stroke events.

## PROBLEM STATEMENT 
Predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relevant information about the patient.Perform necessary exploratory data analysis before building the model and evaluate the model based on performance metrics other than model accuracy.

## DATASET DESCRIPTION 
The dataset consists of several predictor variables and one target variable, Outcome. Predictor variables includes the age,gender,hypertension,smoking status and so on.,
## Column Description 
Id unique identifier gender "Male", "Female" or "Other" 
age age of the patient 
hypertension 0 if the patient doesn't have hypertension, 1 if the patient has hypertension 
heart_disease 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease 
ever_married "No" or "Yes" 
work_type "children", "Govt_jov", "Never_worked", "Private" or "Self-employed" Residence_type "Rural" or "Urban" 
avg_glucose_level average glucose level in blood 
Bmi body mass index
smoking_status "formerly smoked", "never smoked", "smokes" or "Unknown"*
stroke 1 if the patient had a stroke or 0 if not

## DATA SOURCES 
The Dataset Stroke Prediction is taken in Kaggle.Kaggle is an AirBnB for Data Scientists. It’s a crowd- sourced platform to attract, nurture, train and challenge data scientists from all around the world to solve data science, machine learning and predictive analytics problems. Kaggle is the number one stop for data science enthusiasts all around the world Domain 
- Healthcare Format 
-.CSV(Comma Separated value) 
- File - healthcare-dataset-stroke-data.csv 
- Source link -Stroke Prediction Dataset | Kaggle
## ANALYTICS TOOLS 
Python Notebook (Jupyter / google Collab) 
## ANALYTICS APPROACH 
Model Build with Random Forest Classifier (RF) 
Model Build with Support Vector Machine (SVM) 
Model Build with Decision Tree Classifier (DT)
Model Build with K-Nearest Neighbour (KNN) 
Model build with Gradient Boosting Method (GBM) 
Model Build with Extreme Gradient Boosting (XGB) 
Model Build with Adaboost (AB)

## WHAT THE PROBLEM IS 
In the given Dataset, we have a binary classification problem. We will make a prediction on the target variable stroke. Lastly we will build a variety of Classification models and compare the models giving the best prediction on stroke.

## CONCLUSION 
 In this Project Respectively, 
 We have tried to a predict classification problem in Stroke Dataset by a variety of models to classify Stroke predictions in the context of determining whether anybody is likely to get Stroke based on the input parameters like gender, age and various test results or not 
 We have made the detailed exploratory analysis (EDA). 
 missing values are removed in the Dataset by using Simple Imputer with Median
 We have decided which metrics will be used.
 We have analysed both target and features in detail. 
 We have transformed categorical variables into integer by using Label Encoder, so we can use them in the models. 
 We have cross-checked the models obtained from train sets by applying cross validation for each model performance. 
 We have examined the feature importance of some models. 
 Lastly we have examined the results of all models visually with respect to select the best one for the problem in hand. 
 By checking with all the scores like F1_score, Precision, Recall and Accuracy, The Decision Tree and Random Forest gives the best results while comparing with other models. 
 For Respective Dataset the Decision Tree and Random Forest is the Best model for Future Predictions.

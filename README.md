# About
This is a Mini-Project Assignment for SC1015 (Introduction to Data Science and Artificial Intelligence). This project uses data from Kaggle, UCI Heart Disease Data published by MD. REDWAN KARIM SONY (https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)

**Acknowledgements** <br>
Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D. <br>
University Hospital, Zurich, Switzerland: William Steinbrunn, M.D. <br>
University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D. <br>
V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D. <br>

## Contributors
- [@GaryQuah](https://github.com/GaryQuah) : Data cleaning, Multivariate Data Analysis (Numerical & Categorical), Binary Classification
- [@jingjie2205](https://github.com/jingjie2205) : Individual Numerical Data Analysis, Random Forest HyperParameter Tuning, Random Forest , Support Vector Machine

## Problem Definition
- Based On Symptoms Exhibited By The Patients Are We Able To Predict If They Have Heart Disease?

## Models Used
1. Binary Classification - Linear Regression
2. Random Forest + Random Forest Hyperparameter Tuning Using RandomizedSearchCV & GridSearchCV
4. Support Vector Machine
5. Decision Tree

## Data Insights From Exploratory Data Analysis
- Numerical Data : Age, rest_blood_pressure, cholesterol_level , max_heart_rate
-- Age & Max Heart Rate Could Have A Relationship With The Presence Of Heart Disease <br>
- Categorical Data : diabetic, resting_ecg, sex, exercise_angina, chest_pain
-- Type Of Chest Pain, Exercise Angina, Sex Could Have A Relationship With The Presence Of Heart Disease

## Conclusion From Machine Learning
- We Are Able To Predict The Presence Of Heart Disease Using Binary Classification Which Has The Highest Accuracy Out Of The Different Models Used 73 % Of The Time.
- This Model Has A 76% True Positive Rate (TPR) , A False Negative Rate Of 24%, A 45% False Positive Rate (FPR).
- By Creating A Receiver Operating Characteristics (ROC) Curve, We Are Able To Visualise The Trade-Off Between TPR and FPR.
- The Area Under The Curve, Representing This RelationShip Has A Value Of 0.70. Comparing This Value To The Value Of 0.5, We Are Able To Predict The Presence Of Heart Disease At A Much Better Rate Than Simply Guessing At Random.
- Exercise Angina, Age, Blood Pressure, Cholesterol and Max Heart Rate Plays A Large Role In Predicting Heart Disease.
> Although The Models Prediction Accuracy Not Be Extremely High, We Are Able To Minimally Detect A High Possibility Of The Presence Of Heart Diseease. If A Person Is Speculated To Have Heart Disease Using This Model, They Should Be Examined Early In Order To Receive Early Treatment.

## Data Insights From Machine Learning
- Exercise Angina, Age, Blood Pressure, Cholesterol And Heart Rate Play A Big Part In Predicting Heart Disease.
- Resting Max Heart Rate, ECG, Chest Pain, and Gender Play A Low Part In Predicting Heart Disease
- People With Chest Pain Of Type Non-Anginal or Atypical Angina With Age Lesser Than 56 And Blood Pressure Lesser Than 191 Generally Have No Heart Conditions.
- Patients With Chest Pain: Typical Angina Or Asymptomatic With Exercise Induced Angina And Normal Or Lv Hypertrophy Resting ECG generally Have Heart Disease.
  
## What did we learn?
1. Binary Classification - Linear Regression Is A Good Model Used To Predict Binary Values (True or False)
2. Random Forest - A Better Model As Compared To Decision Tree Which Also Addresses Over-Fitting Problem
3. HyperParameter Tuning - We Learnt How We Can Effectively Tune Our Model Parameters For Optimal Results
4. Binary Predictions Usage Of False Negative Rate For Binary Prediction Instead Of Just True Positive Rate & False Positive Rate

## References - Dataset
1.  MD, R. (2020). UCI Heart Disease Data. Www.kaggle.com. https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

## References - Explanation Of Data
1. Stern, et al. (2003, October 7). How aging affects your heart. Aging and Diseases of the Heart. https://www.ahajournals.org/doi/full/10.1161/01.cir.0000086898.96021.b9 
2. LeWine, H. E. (2023, June 13). What your heart rate is telling you. Harvard Health. https://www.health.harvard.edu/heart-health/what-your-heart-rate-is-telling-you#:~:text=Your%20maximum%20heart%20rate%20plays,of%20heart%20attack%20and%20death.
3. Singapore Heart Foundation. (2022). Heart disease statistics. https://www.myheart.org.sg/health/heart-disease-statistics/
4. Doctor Anywhere. (2022). DA-lifebuoy preventive health survey. https://doctoranywhere.com/preventive-health-survey-2022/
5. Professional, C. C. M. (n.d.). Cholesterol Numbers and What They Mean. Cleveland Clinic. https://my.clevelandclinic.org/health/articles/11920-cholesterol-numbers-what-do-they-mean

## References - Creation Of Code
1. Navlani, A. (2019, December). Python Logistic Regression Tutorial with Sklearn & Scikit. Www.datacamp.com. https://www.datacamp.com/tutorial/understanding-logistic-regression-python
2. Box Plot. (2021, January 19). GeeksforGeeks. https://www.geeksforgeeks.org/box-plot/
3. Countplot using Seaborn in Python. (2021, June 12). GeeksforGeeks. https://www.geeksforgeeks.org/countplot-using-seaborn-in-python/
4. Hyperparameter Tuning Random Forest (2022, December 30). https://www.geeksforgeeks.org/random-forest-hyperparameter-tuning-in-python/
5. Support Vector Machine (SVM) Algorithm (2023, June 10). Support Vector Machine (SVM) Algorithm. GeeksforGeeks. https://www.geeksforgeeks.org/support-vector-machine-algorithm/
6. Feature importances with a forest of trees. (n.d.). Scikit-learn. https://scikit-learn.org/stable/auto_examples/ensemble/plot_forest_importances.html

‌


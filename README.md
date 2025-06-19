# MLPProject
## **Project Overview**
This project was completed as part of the Machine Learning Practice course in the Data Science Diploma program at IIT Madras.
The goal of the Kaggle competition was to predict whether a machine is infected by malware, using system telemetry data collected by antivirus software. The dataset contains various system-level features such as OS details, processor type, RAM, antivirus settings, and more.

## **Dataset Description**
-train.csv: Labeled data with machine features and malware infection status (target)

-test.csv: Unlabeled data to make predictions

-sample_submission.csv: Sample format for Kaggle submission

Each row represents one machine, identified by MachineID. The target column is 1 if malware was detected, and 0 otherwise.

## **Process Summary**
### Exploratory Data Analysis (EDA)
-Analyzed feature types and distributions

-Identified missing values and potential outliers

-Explored feature-target relationships

### Preprocessing
-Handled missing values appropriately

-Encoded categorical variables

-Scaled numeric features where required

-Performed feature selection to reduce dimensionality

### Models Used (with Hyperparameter Tuning)
-Logistic Regression

-Decision Tree Classifier

-Random Forest Classifier

-XGBoost Classifier

## Evaluation
-Evaluation metric: accuracy_score()

-Cross-validation used for robust model comparison

-Final predictions generated on the test set

## Results
-Best Score: 0.63300

-Leaderboard Rank: 266 (Kaggle)

## File Included
23DS3000136-notebook-t12025.ipynb: Jupyter Notebook containing EDA, preprocessing, model training, evaluation, and final prediction

## Conclusion
This project demonstrates the use of classical machine learning techniques for malware detection. Careful data preprocessing, model selection, tuning, and feature engineering were key to achieving a competitive score in the leaderboard.

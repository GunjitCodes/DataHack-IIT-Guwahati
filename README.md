# DataHack-IIT-Guwahati
The Data Analytics Hackathon aims to provide a platform for students to apply the knowledge and skills acquired during the preceding Summer Analytics Workshop. This event encourages innovative thinking, problem-solving, and teamwork, fostering a competitive yet collaborative environment.



Naturally, the following is a concise synopsis in bullet points:

#Data handling: Training datasets (training_set_labels.csv and training_set_features.csv) and testing dataset (test_set_features.csv) were uploaded and integrated.

#OneHotEncoder and SimpleImputer were used to encode categorical features and impute missing values.
#Modelling Methodology:
two Random Forest classifiers were trained: one to forecast whether or not they will get the xyz flu vaccination.
Another to forecast the receipt of seasonal flu vaccinations.
The model was then evaluated using the ROC AUC score, which is applicable to binary classification issues.
#Forecast and Remit:
made assumptions based on the trained models on the test set.
made a submission file (submission.csv) with the respondent IDs and the anticipated odds for each vaccination.

#Important Points:

#Data Preparation: To maintain data quality and enable the model to learn, encoded variables were imputed.

#Random Forests was selected as the model of choice because of its robustness in handling complex data sets and its capacity to manage variable interactions.
Evaluation Metric: The accuracy of a model's prediction regarding a person's likelihood of receiving a vaccination or not is measured by the ROC AUC score, which shows how well a model performs in the binary classification task. This led to precise forecasts.

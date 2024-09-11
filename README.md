### Cardiac_Capstone_Part1
**Mahalakshmi Ganesan**

#### Executive summary

#### Rationale
Cardiovascular Disease is the leading cause of death in the US. This question is important because it can help with detecting the first possible signs of such disease in a patient. This can help doctors and patients pursue further testing to confirm the diagnosis and begin early actions in treating a patient's cardiovascular disease. This analysis will help by allowing non-AI/ML personnel to input the values of the specific demographic and vital signs variables and determine if there would be the possibility of cardiovascular disease.

#### Research Question
Based on patients' demographics and vital signs data, can we predict the presence of cardiovascular disease? 

#### Data Sources
For this project, my dataset was ontained from Kaggle.com. The specific link is [Cardiovascular Disease](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset).

#### Methodology
Provided that the outcome variable is binary and that this dataset is quite large, I will be using Logistic Regression.
Upon analysis of the dataset, I had noted significant outliers and issues with the data. I decided that the analysis would be specifically regarding subjects with a height between 140cm and 200sm, weight greater than 45kg, Systolic Blood Pressure between 90mmHg and 180mmHg and Diastolic Blood Pressure between 60mmHg and 120mmHg.

#### Results
Using Logistic Regression, I was able to find that Systolic Regression, Age, Cholesterol and Weight are 4 of the most important factors based on their Logistic Regression Coefficient values when determining if a subject will have presence of Cardiovascular Disease. Additionally, I was able to determine that Gender, Smoking, Height and Alcohol Intake are 4 of the least important factors when determine the presence or absence of Cardiovascular Disease. The Logistic Regression analysis also has a Test and Training Accuracy of approximately 0.73 and 0.72 respectively. This analysis also has Accuracy of 0.75, Precision of 0.75, Recall od 0.66 and Roc_AUC of 0.78, 

#### Next steps
For next steps for the research team, I would recommend that they focus on subjects' Systolic Blood Pressure as the key factor and follow up with analyzing their Age, Cholesterol and Weight. If there are senior subjects with high Systolic Blood Pressure, high Cholesterol and high weight, then I would recommend that those subjects are tested early for Cardiovascular Disease to ensure that they do not have detrimental health issues that impact their quality of life.

#### Outline of project

- [Capstone_Part_1.ipynb](https://github.com/maha0491/Cardiac_Capstone_Part1/blob/2fe9ce82801291bf9bfec347eb0b7335306eab35/Capstone_Part_1.ipynb)

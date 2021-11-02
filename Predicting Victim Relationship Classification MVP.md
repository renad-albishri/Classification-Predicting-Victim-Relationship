# Victim Relationship Prediction Using Classification MVP
## Objective
The objective of this project is to predict the perpetrator's relationship with the victim, by using Classification as a part of machine learning.
## Preprocessing
- We obtained [Homicide dataset](https://www.kaggle.com/murderaccountability/homicide-reports) data from Kaggle. Which contains 638454 rows and 24 columns.<br/>
- Perform EDA: <br/>
  - Cleaning.
  - Visualization.
- Building models for classification.
## Findings
After obtaining the relationship between features and target, we present them in the below pairplot
<img src = 'https://github.com/renad-albishri/Classification-Predicting-Victim-Relationship/blob/main/images/pairplot.jpeg'/>
As shown above, there is low-overlap between **Vic_Gender** and our target, which may help us to improve classification results.
<br/><br>
Then, we built baseline model as a start step, which gaves us a high score in both training and validation **0.954**, and **0.953** respectively; and as a next step, we will build more models to get the best score.

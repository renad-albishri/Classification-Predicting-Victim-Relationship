# Predicting Victim Relationship Classification Final Report
## Abstract
Violent crimes are one of the world's most severe social issues, posing a threat to peace and security.
Also, many people feel anxious and terrified by it. The goal of this project is to predict the perpetrator's relationship with the victim in order to
identify a pattern that may be used to control and limit these crimes, by using Classification as a part of machine learning.
## Data Description
We choose Homicide dataset which contains murders from the FBI's Supplementary Homicide Report from 1976 to 2014.
This dataset contains 638454 rows and 24 columns, our features are age , race, gender, ethnicity of victims and perpetrators,
and weapon used ..etc. And our target is relationship between the victim and perpetrator. <br/>
## Algorithms
### Models Evaluation and Selection
We have been evaluate the data over 7 models using Simple Validation approach, which are: __Logistic Regression__, __Decision Tree Classifier__ , __Random Forest Classifier__, __Bernoulli NB__, __Multinomial NB__,
__Gaussian NB__, and __Gradient Boosting Classifier__.
Accordingly, we choose __Gaussian NB__ because it has the greatest score.
### Feature Engineering
We tried 4 attempts to optimize the model's score, and we just approved 1 of them.
1. Add the difference in age between victim and perpetrator as an additional feature, and we skip this attemp.
2. Same previous point, but also with delete the age feature in both victim and perpetrator, and we approved this attemp.
3. Add feature that count the number of each weapon used in each state.
4. Add column that count the number of crimes in each state.
### Best Model Scores
with 78 features (because we convert categorical values to dummy).
#### Training
__Score__: 0.99878<br/>
#### Testing
__Score__:  0.99838<br/>
## Tools
Here the basic tools we used in our project: <br/>
Technologies: python, and Jupyter Notebook with python libraries:
- EDA
  - pandas
  - matplotlib
  - numpy
  - seaborn
- Classification
  - scikit-learn
## Communication
The provided slides.
## Conclusion
We aim to control and limit crimes; to achieve that we used Classification algorithm to predict the perpetrator's relationship with the victim, by training and testing our model on the extracted data.

## IBM-HR-Analytics-Employee-Attrition-and-Performance-Prediction

### HR ANALYTICS
HR analytics is the process of collecting and analyzing Human Resource (HR) data in order to improve an organization’s workforce performance. The process can also be referred to as talent analytics, people analytics, or even workforce analytics. This method of data analysis takes data that is routinely collected by HR and correlates it to HR and organizational objectives. Doing so provides measured evidence of how HR initiatives are contributing to the organization’s goals and strategies.

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### OBJECTIVE

Employee attrition is the rate at which employees leave a company. The goal of this analysis is to model employee attrition and determine the most dominant contributing factors that govern this turnover. Through this kind of analysis, we can understand how many employees are likely to leave, while also determining which employees are at the highest risk and for what reasons.

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### DATASET
This is a hypothetical dataset created by IBM data scientists. The dataset has (1470R X 35C) that contains numeric and categorical data types describing each employee’s background and characteristics, and labeled with whether they are still in the company or whether they have gone to work somewhere else. 

Dataset Link:
https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### LIBRARIES USED:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- HvPlot
- SciPy
- Sklearn
- XGBoost
- LightGBM
- CatBoost
- Warnings

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### MODEL EVALUATION

|         ALGORITHMS        | TRAINING  DATA ACCURACY SCORE | TESTING DATA ACCURACY SCORE |
| --------------------------| ----------------------------- | --------------------------- |
| Logistic Regression       |            0.9271             |           0.8639            |
| Random Forest             |            0.8902             |           0.8413            |
| Support Vector Machine    |            0.9349             |           0.8662            |
| XGBoost                   |            1.0000             |           0.8526            |
| LightGBM                  |            1.0000             |           0.8390            |
| CatBoost                  |            0.9845             |           0.8503            |
| AdaBoost                  |            0.9077             |           0.8322            |

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### COMPARING MODEL PERFORMANCE USING ROC CURVE

<div align="center"> <img src="https://github.com/shantanu1109/IBM-HR-Analytics-Employee-Attrition-and-Performance-Prediction/blob/main/IMAGES/File-5-ROC-Curve.png" alt="ROC Curve"> </div>



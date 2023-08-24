<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

<div align= "center">
    <h2> IBM-HR-Analytics-Employee-Attrition-and-Performance-Prediction </h2><br>
</div>


<div align= "center">
    <img src="https://media0.giphy.com/media/3o85xGdsSCHfTPBJok/giphy.gif?cid=ecf05e47l31i9etrpyq28fkfu8e6m1kpgrwngdx1ga4zx5n6&rid=giphy.gif&ct=g">
</div>

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :writing_hand: HR ANALYTICS
HR analytics is the process of collecting and analyzing Human Resource (HR) data in order to improve an organization’s workforce performance. The process can also be referred to as talent analytics, people analytics, or even workforce analytics. This method of data analysis takes data that is routinely collected by HR and correlates it to HR and organizational objectives. Doing so provides measured evidence of how HR initiatives are contributing to the organization’s goals and strategies.

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :round_pushpin: OBJECTIVE

Employee attrition is the rate at which employees leave a company. The goal of this analysis is to model employee attrition and determine the most dominant contributing factors that govern this turnover. Through this kind of analysis, we can understand how many employees are likely to leave, while also determining which employees are at the highest risk and for what reasons.

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :innocent: MOTIVATION
The project stems from the potential to improve employee satisfaction, reduce costs, enhance organizational performance, and create a positive workplace culture. It's an opportunity to use data and analytics to make meaningful changes that benefit both employees and the organization as a whole.

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :triangular_ruler: SYSTEM ARCHITECTURE

<div align="center"> <img src="https://github.com/shantanu1109/IBM-HR-Analytics-Employee-Attrition-and-Performance-Prediction/blob/main/IMAGES/File-5-System-Architecture-Diagram.jpeg" alt="System Architecture"> </div>

#### The methodology for IBM-HR-Analytics-Employee-Attrition-and-Performance-Prediction is as follows:-
```
- **Load the Dataset:** The IBM HR Analytics Attrition Dataset is loaded using the pd.read_csv() function. The head() and info() methods are used to display the first few rows and get information about the dataset, respectively.
- Knowing the Dataset: Basic Information about the dataset is generated; numerical and categorical attributes are enlisted.
- Data Cleaning: Any missing values in the dataset are dropped using the dropna() method.
- Data Visualization: Matplotlib and Seaborn libraries are used to visualize the data. 
- Statistical Analysis: The ANOVA Test is performed to analyze the Numerical Features' Importance in Employee Attrition, while the Chi-Square Test to Analyze the Categorical Feature Importance in Employee Attrition.
- Data Preprocessing: The target variable 'Attrition' is mapped to binary values (1 for 'Yes' and 0 for 'No'). Selected features are extracted from the dataset and one-hot encoded using the get_dummies() function.
- Splitting the Dataset: The dataset is split into training and testing sets using the train_test_split() method from scikit-learn.
- Implementing Machine Learning Algorithms: Logistic Regression, XGBoost, CatBoost, AdaBoost, LightGBM, Decision Tree, and Random Forest classifiers are initialized and trained using the training data.
- Model Evaluation: The accuracy score and confusion matrix are computed to evaluate the performance of each algorithm on the testing data.
- Results: The results, including the accuracy and confusion matrix, are printed for each algorithm.
- Model Performance Comparison: The hvPlot library is used to visualize the ROC curve diagram comparing the performance of all models used.
```

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :file_folder: DATASET
This is a hypothetical dataset created by IBM data scientists. The dataset has (1470R X 35C) that contains numeric and categorical data types describing each employee’s background and characteristics, and labeled with whether they are still in the company or whether they have gone to work somewhere else. 

#### Dataset Attributes
```
01] Age
02] Attrition
03] BusinessTravel
04] DailyRate
05] Department
06] DistanceFromHome
07] Education
08] EducationField
09] EmployeeCount
10] EmployeeNumber
11] EnvironmentSatisfaction
12] Gender
13] HourlyRate
14] JobInvolvement
15] JobLevel
16] JobRole
17] JobSatisfaction
18] MaritalStatus
19] MonthlyIncome
20] MonthlyRate
21] NumCompaniesWorked
22] Over18
23] OverTime
24] PercentSalaryHike
25] PerformanceRating
26] RelationshipSatisfaction
27] StandardHours
28] StockOptionLevel
29] TotalWorkingYears
30] TrainingTimesLastYear
31] WorkLifeBalance
32] YearsAtCompany
33] YearsInCurrentRole
34] YearsSinceLastPromotion
35] YearsWithCurrManager
```

Dataset Link:
https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :memo: LIBRARIES USED:
```
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
```

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :warning: PREREQUISITES

```
- Python Programming
- Data Science
- Data Pre-processing
- Data Visualization
- Statistical Analysis
- Machine Learning Algorithms
- Performance Metrics.
```

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :sparkles: MODEL EVALUATION

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

### :chart_with_upwards_trend: COMPARING MODEL PERFORMANCE USING ROC CURVE

<div align="center"> <img src="https://github.com/shantanu1109/IBM-HR-Analytics-Employee-Attrition-and-Performance-Prediction/blob/main/IMAGES/File-6-ROC-Curve.png" alt="ROC Curve"> </div>

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :scroll: LICENSE
The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
 
<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

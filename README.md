# AI/ML Project: Boston Housing Price Prediction 🏘️
<p align="center"><img src="https://user-images.githubusercontent.com/54996245/144908266-653a168e-be3c-43ed-abee-f2ae4a4598c9.jpg" style="width: 1000px;"/></p>

### Description:
Housing Values in Suburbs of Boston
The medv variable is the target variable. \
The Boston data frame has 506 rows and 14 columns.

**This data frame contains the following columns:**
* crim --> per capita crime rate by town.
* zn --> proportion of residential land zoned for lots over 25,000 sq.ft.
* indus --> proportion of non-retail business acres per town.
* chas --> Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).
* nox --> nitrogen oxides concentration (parts per 10 million).
* rm --> average number of rooms per dwelling.
* age --> proportion of owner-occupied units built prior to 1940.
* dis --> weighted mean of distances to five Boston employment centres.
* rad --> index of accessibility to radial highways.
* tax --> full-value property-tax rate per \$10,000.
* ptratio --> pupil-teacher ratio by town.
* black --> 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.
* lstat --> lower status of the population (percent).
* medv --> median value of owner-occupied homes in \$1000s.

**Source**
Harrison, D. and Rubinfeld, D.L. (1978) Hedonic prices and the demand for clean air. J. Environ. Economics and Management 5, 81–102.
Belsley D.A., Kuh, E. and Welsch, R.E. (1980) Regression Diagnostics. Identifying Influential Data and Sources of Collinearity. New York: Wiley.

### Objective:
- Understand the Dataset & cleanup (if required).
- Build Regression models to predict the sales w.r.t a single & multiple feature.
- Also evaluate the models & compare thier respective scores like R2, RMSE, etc.

### Stractegic Plan of Action:
  
**We aim to solve the current problem statement by creating plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Feature Selection/Extraction
5. Predictive Modelling
6. Project Outcomes & Conclusion

### Some Visuals of the Project:
**1. Target Variable Distribution**

<p align="left"><img src="https://user-images.githubusercontent.com/54996245/144908337-3999c2d0-97ec-415a-8dfa-316dfeb1a090.png" /></p>

**2. Categorical Feature-set Distribution**
  
![image](https://user-images.githubusercontent.com/54996245/144908425-9e3158af-0d7f-4f65-a312-96ff803d3f72.png)

**3. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/144908438-9faae9ca-4fd5-48b6-91a6-7cd7582b498e.png)
![image](https://user-images.githubusercontent.com/54996245/144908464-6a515ab1-6948-42e1-a777-0e0a6edc837e.png)

**4. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/144909166-d897f458-8ab8-4521-8ce4-3ac6468eb806.png)

**5. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/144908532-6e0c6524-29c6-4b60-b596-81421ea377d0.png)

**6. Correlation Plot**
  
![image](https://user-images.githubusercontent.com/54996245/144908553-5a3b0cbe-2d58-49d7-b974-6eb7cbcfc109.png)

**7. Feature Selection/Extraction - VIF, RFE & PCA Techniques:

![image](https://user-images.githubusercontent.com/54996245/144908720-8d7cc2ef-6b3d-40df-9285-7bd8b3446895.png)
![image](https://user-images.githubusercontent.com/54996245/144908739-dc8e33ab-33bf-43b8-b803-d6864a9778ca.png)
![image](https://user-images.githubusercontent.com/54996245/144908744-42c79932-2dcb-427f-9024-49aac69de5a5.png)
![image](https://user-images.githubusercontent.com/54996245/144908756-fb21f6f8-0852-4064-afe4-069ad43e70ac.png)

**8. Multiple Linear Regression Prediction & Residual Normality Check**
  
![image](https://user-images.githubusercontent.com/54996245/144908814-753b7014-b49d-4bf6-907a-44bc38c34670.png)

**9. Polynomial Degrees Comparison**

![image](https://user-images.githubusercontent.com/54996245/144908900-56eb5db5-6540-4801-a782-b5d66bbf91da.png)

**10. Predictions**

![image](https://user-images.githubusercontent.com/54996245/144908866-c380a46f-9a13-4496-8022-e1fae0acf7bf.png)


**11. ML Algorithm's Scores Comparison (R2& RMSE) for the Ad Budge Dataset**

![image](https://user-images.githubusercontent.com/54996245/144908927-1eaa8931-ec0a-4475-afe2-8490303d55bd.png)
![image](https://user-images.githubusercontent.com/54996245/144908937-0e73ca6f-37b7-49c7-b1b4-e5566723115b.png)


### Here are some of the key outcomes of the project:
- The Dataset was quiet small totally just 506 samples & after preprocessing 8.1% of the datasamples were dropped. 
- Visualising the distribution of data & their relationships, helped us to get some insights on the feature-set.
- The features had high multicollinearity, hence in Feature Extraction step, we used VIF & RFE Techniques to drop highly correlated features.
- Testing multiple algorithms with default hyperparamters gave us some understanding for various models performance on this specific dataset.
- While, Polynomial Regression (Order-2) gave the best overall scores for the current dataset, yet it wise to also consider simpler models like MLR & ENR as they are more generalisable.

CONCRETE STRENGTH

 Predicting the compressive strength of concrete using ML methods.

EXISTING SOCIETAL ISSUE:

 In earlier days, the concrete strength is measure through other traditional methods like using drill holes, weight spring, or using sensors. But that requires a      significant destruction of test sample and thereby increasing the cost. The recommended wait time for testing the cylinder is 28 days to ensure correct results. This consumes a lot of time and requires a lot of labour to prepare different prototypes and test them. Also, this method is prone to human error and one small mistake can cause the wait time to drastically increase.

PROPOSED SOLUTION:
The focus of this project is the application of machine learning process and their suitability to model concrete compressive strength compared with early models obtained from the literature and compared with some conventional approaches and also a recoomendation system is developed by applying various ML methods, to predict the concrete strength from its components accurately and then looking for the optimal combination of components which increases the strength.


 
![CEMENT STRENGTH PREDICTION PICTURE](https://user-images.githubusercontent.com/105592316/198953187-95837ff6-95ad-4fa3-933f-f8dde4f61f5b.jpg)

DATA DESCRIPTION:
Data is obtained from UCI Machine Learning Repository and this dataset is used for all ML Algorithms. https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength

Number of instances - 1030 Number of Attributes - 9 Attribute breakdown - 8 quantitative inputs, 1 quantitative output

Attribute information:
Inputs: Cement, Blast Furnace Slag, Fly Ash, Water, Superplasticizer, Coarse Aggregate, Fine Aggregate, All above features measured in kg/$m^3$, Age (in days),

Output: Concrete Compressive Strength (Mpa)

Dataset used for Deep Nueral Network is https://www.kaggle.com/maajdl/yeh-concret-data

MODELLING AND EVALUATION:
ML Algorithms used: Linear regression, Lasso regression, Ridge regression, Random Forests

Metric - Since the target variable is a continuous variable, regression evaluation metric RMSE (Root Mean Squared Error) and R2 Score (Coefficient of Determination) have been used. And a recommendation system is developed as which algorithm is best choice for predicting accurate concrete strength.

CONCLUSION:
Analysed the Compressive Strength and used Machine Learning to Predict the Compressive Strength of Concrete. We have used Linear Regression and its variations, Decision Trees and Random Forests to make predictions and compared their performance. Random Forest Regressor has the lowest RMSE and is a good choice for this problem. Also, we can further improve the performance of the algorithm by tuning the hyperparameters by performing a grid search CV.

 APP LINK 
 https://lively-goal-366110.el.r.appspot.com/

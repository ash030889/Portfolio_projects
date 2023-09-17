Real Estate project:
AIM & OBJECTIVE:
•	People looking to buy a new home tend to be more conservative with their budgets and market strategies.
•	This project aims to analyse various parameters like furnishing status, area, preferred area, no. of bedrooms, bathrooms, stories, parking etc. and predict the house price accordingly. 
•	This application will help customers to invest in an estate without approaching an agent.
•	To provide a better and fast way of performing operations. 
•	To provide proper house price to the customers. 
•	To provide best price to user without getting cheated. 
•	To enable user to search home as per the budget. 
•	The aim is to predict the efficient house pricing for real estate customers with respect to their budgets and priorities. By analysing previous market trends and price ranges, and also upcoming developments future prices will be predicted.  
•	We used Linear Regression, Decision Tree Regressor, Random Forest Regressor algorithms in machine learning for predicting the house price trends. To get better accuracy score and predict more efficient house price trend. 
PROPOSED SYSTEM 
• Linear Regression is a supervised machine learning model that attempts to model a linear relationship between dependent variables (Y) and independent variables (X). Every evaluated observation with a model, the target (Y)’s actual value is compared to the target (Y)’s predicted value, and the major differences in these values are called residuals. The Linear Regression model aims to minimize the sum of all squared residuals. Here is the mathematical representation of the linear regression: 
Y= a0+a1X+ ε
The values of X and Y variables are training datasets for the model representation of linear regression. When a user implements a linear regression, algorithms start to find the best fit line using a0 and a1. In such a way, it becomes more accurate to actual data points; since we recognize the value of a0 and a1, we can use a model for predicting the response. 
 

• As you can see in the above diagram, the red dots are observed values for both X and Y.
• The black line, which is called a line of best fit, minimizes a sum of a squared error. 
• The blue lines represent the errors; it is a distance between the line of best fit and observed values.
• The value of the a1is the slope of the black line.
					BLOCK DIAGRAM

 
PROPOSED SYSTEM PHASES 
Phase 1 Collection of data:
Data processing techniques and processes are numerous. We collected data for USA/Mumbai real estate properties from various real estate websites. The data would be having attributes such as Location, carpet area, built-up area, age of the property, zip code, price, no of bedrooms etc. We must collect the quantitative data which is structured and categorized. Data collection is needed before any kind of machine learning research is carried out. Dataset validity is a must otherwise there is no point in analysing the data.

Phase 2: Data pre-processing:
Data pre-processing is the process of cleaning our data set. There might be missing values or outliers in the dataset. These can be handled by data cleaning. If there are many missing values in a variable we will drop those values or substitute it with the average value.

Phase 3 Visualization of Dataset:
•	In this data set we prepared two chart 1st chart is between furnishing status and price.
•	2nd chart is between area and price. (Because we have huge data so we took to 20 rows data for both charts) 
•	In 1st chart we can see most of furnished house has more price compare to unfurnished and semi-furnished houses.
•	In 2nd chart we can see area of house very less effect price of house.

Phase 4: Dividing Data set into X and Y:
In this phase we can divide data set (pre-processed) into X independent variables and Y dependent variables. So we put house price as dependent variable and rest of all is independent variables because they can effect house price.
  
Phase 5: Training the model:
 Since the data is broken down into two modules: a Training set and Test set, we must initially train the model. The training set includes the target variable. The decision tree regressor algorithm is applied to the training data set. The Decision tree builds a regression model in the form of a tree structure.
 
Phase 6.1: Linear Regression model:in the LinearRegression model we can see that acurracy obtained is 67% which is not very good so we can try another models than we can get better accuracy.

 
Phase 6.2: Decision Tree model:here we used Decision Tree model we can see that acurracy obtained is 82% which is quite good but we can also try another models to get better accuracy or not.

 
Phase 6.3: Random Forest model:Random Forest model we can see that acurracy obtained is 86% which is quite good. we used three model and realised Random Forest MLM is better than another two model for this housinng dataset.
 

Conclusion:
Here we used Random Forest model we can see that acurracy obtained is 86% which is quite good. We used three model and realised Random Forest MLM is better than another two model for this housing dataset.
Enter the new dataset for predict the house price:
 


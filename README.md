Here We have given Data OF Houses According To their Area And Particular Description 
We have to analye data And Find Patterns And Make prediction that if user want to buy a House He should get Predicted Cost of that Housse through our Project 


1. Read the Data
2. Drop unnecessary columns(Columns with no statitical importance)
3. Missing Data treatment
4. Exploratory Data Analysis
	4.1 Check for Skew in X columns
	4.2 Remove skew
	4.3 Correlation
	4.4 Drop cols from X having very minute or no correlation
5. Preprocessing	
	5.1 Standardization of con columns
	5.2 OHE of categorical columns
6. Divide data in training & testing set(Random state: 31)0.8,0.2
7. Create a backward elemination OLS model
8. Remove unncessary columns on the basis of pval
9. Create a Linear Regression model on the basis of selected columns.
10. Find training | testing error --> Overfitting or not
11. Check for colinearity and multicolinearity
12. Ridge, Lasso
13. Create a Tuning grid
14. GrisearchCv model to find best penalty value for Ridge | Lasso
15. Using the best value, create a Ridge | Lasso Model 
16. Check for overfitting.
17. Using the best model you need to make final predictions(This step will be explained in class)

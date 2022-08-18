# ScaniaAB
<p align="center"><a href="url"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTMXd9V4hjxjpyYYIjT5pej2I6HcLX84HhNwg&usqp=CAU" height="200" width="300" ></a> </p> <br>

### Business Context 
Scania AB is a major Swedish manufacturer focusing on automobiles. It also manufactures diesel engines for heavy vehicles as well as marine and general industrial applications. The company is planning to enter the American Market by setting up their manufacturing unit there.

### Problem Statement
To identify the factors that influence the price of cars in America, based on which they can manipulate the design of their cars and can take a good start in the business. <br> <br>
The objectives include:
1. Variables that affect the price of cars in America<br>
2. Analyze the impact of each feature on the price<br>
3. Suggest possible requirements for Scania AB to work on<br>

### Solution Developed
1. Data Cleaning <br>
2. EDA Analysis<br>
3. Data Preparation<br>
4. Splitting into train and test dataset<br>
5. Feature Scaling<br>
6. Model<br>
7. Residual Analysis<br>
8. Predicting the Model<br>
9. Model Evaluation<br>

### Suggestions
1. **Engine Size**: this is one of the most important features in determining the price. Greater, the better<br>
2. **Engine Type**: avoid OHCV, one better option could be OHCF.<br>
3. **Fuel System**: IDI is a good suggestion. It does not affect the price much though.<br>
4. **No.of Cylinders**: avoid 12, choose either 2 or 5. Although looking at the 2 models it seems that 2 has more impact on the price.<br>
5. **Peak RPM**: both the models show that it has some significant on the price of a car <br>
6. **Car length**: along with this, during the analysis it was evident that curb weight, horsepower & car width are also important features. Although they were highly correlated to the other features, it is important to note the significance of these features as well.<br>

### Improvements
While our model has given a good insight on the factors that affect the price of cars in the USA, we can always improvise on the model by trying out different regression models such as Linear Regression. Additionally it is clear that the existing features were more than useful, it could also be enhanced further by adding more derived variables.

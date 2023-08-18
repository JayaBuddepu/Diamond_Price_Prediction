**GOAL**

The goal is to predict price of Diamond.

- There are 3 variables with an ordered factor structure: cut, color, & clarity. An ordered factor arranges the categorical values in a low-to-high rank order. For example, there are 5 categories of diamond cuts with “Fair” being the lowest grade of cut to ideal being the highest grade.

- There are 6 variables that are of numeric structure: carat, depth, table, x, y, z

- There is 1 variable that has an integer structure: price


**WHAT I HAD DONE**
- Discussed some major columns on which price of Diamond depends.
- Handling outliers of diagnosis columns. As, it is very important because at last we're price of Diamond.
- Then I used different Linear Regression model present in sklearn to train the model.
- Use Correlation coefficients to measure how strong a relationship is between two variables.

**MODELS USED**
-  Linear Regression
-  KNN Regressor

**LIBRARIES NEEDED**
- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn

**CONCLUSION**

By using Logistic Regression I got 
 ```
    Accuracy of training data: 86.03402181161945
    Accuracy of testing data: 85.5896797526322
 ``` 
 
 By using KNN Regressor I got 
 ```
    Accuracy of training data: 89.77109214576862
    Accuracy of testing data: 87.22158536741495
 ``` 

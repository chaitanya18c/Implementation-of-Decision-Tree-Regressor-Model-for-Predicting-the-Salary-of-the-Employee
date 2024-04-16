# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import pandas
2. Import Decision tree classifier
3. Fit the data in the model
4. Find the accuracy score

## Program:
```python
/*
Program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.
Developed by: CHAITANYA P S
RegisterNumber:  212222230024
import pandas as pd
data=pd.read_csv("/content/Salary.csv")
data.head()
data.info()
data.isnull().sum()
from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()
data["Position"]=le.fit_transform(data["Position"])
data.head()
x=data[["Position","Level"]]
x.head()
y=data["Salary"]
from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=2)
from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=2)
from sklearn import metrics
mse=metrics.mean_squared_error(y_test,y_pred) 
mse
r2=metrics.r2_score(y_test,y_pred)
r2
dt.predict([[5,6]])

*/
```

## Output:
#### data.head()
![243093531-74928a7e-5490-4f21-a455-081786ea5ce3](https://github.com/chaitanya18c/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/119392724/d00a900d-1a3c-4cdf-b796-51676296a5ef)

#### data.info()
![243093535-ca791c21-ecb7-4869-95a4-3b833cc925e3](https://github.com/chaitanya18c/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/119392724/cec3b1f2-ac57-496f-acbf-589ef271d446)

#### isnull() and sum()
![243093541-e349e8a7-c2f3-4afe-9707-603ee307cd5b](https://github.com/chaitanya18c/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/119392724/b442e83d-3ae1-4f2a-82a7-b44bb946a5ba)

#### data.head() for salary 
![243093548-fa80dab8-37c3-44c8-86ac-9301b2128636](https://github.com/chaitanya18c/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/119392724/3ab56310-9875-43ab-87eb-f44315e6ed61)

#### MSE value
![243093595-d48a86c5-919c-47f2-8ffd-8ca51ca8687c](https://github.com/chaitanya18c/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/119392724/85fb6f67-1c1f-436c-a060-c3f2193c9c2b)

#### r2 value
![243093601-c9c2d65d-f9ff-4a10-9a8e-7270c067d025](https://github.com/chaitanya18c/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/119392724/a78060f6-5f47-4d62-8a43-915f0e2eaaaf)

#### data prediction
![320183852-485e2f7f-5060-40f2-8ae2-931a8cd39867](https://github.com/chaitanya18c/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/119392724/b2ba4b55-5503-4087-ac6d-34575ac82759)

 
## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.

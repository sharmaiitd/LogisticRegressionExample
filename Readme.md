# Logistic Regression

Logistic regression is similar to linear regression but with a better curve fitting. The logic can be shown as follows: 

![Alt text](lrlogic.png?raw=true "logistic logic")

The code splits the data, does feature scaling, trains the data and then is able to predict. 
Important section is: 
```
# Training the Logistic Regression model on the Training set
from sklearn.linear_model import LogisticRegression
classifier = LogisticRegression(random_state = 0)
classifier.fit(X_train, y_train)
```

![Alt text](lrres.png?raw=true "logistic result")
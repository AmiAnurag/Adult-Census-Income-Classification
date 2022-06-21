
# Adult Census Income Prediction

This project contains implementation of many classifiers and how they work in different scenario. At the end I have chosed a classifier which fits well in the given data , certain hypertuning is also implemented for better outcome. Hosted at : https://income-predictor-flask.herokuapp.com/
____



## Features

- Exploratory data Analysis
- Feature selection and Feature Engineering
- Classification report
- Hyper parameter Tuning



## Model discussed :


1. **Logistic Regression** -It is based on log regularized logistic regression. It minimizes log probability.
2. **SGD classifier**- This is a linear classifier that minimizes the cost function using stochastic gradient descent.
3. **Logistic Regression CV** -logistic regression with builtin cross validation
4. **Naive Bayes**
        
        1. Gaussian Nave Bayes --implemet when likelihood of features are gaussian
        
        2. Multinomial Naive Bayes --multinomially distributed data
        
        3. Complement Naive Bayes --works on imbalenced multinomially distributed data set
        
        4. Bernoulli Naive Bayes --works for multivariate bernoulli distributed data
        
        5. Categorical Naive Bayes -- for categorically distributed data
        
        6. Out of core naive bayes model fitting -- for large classification problem

        *note :-> Bernoulli:Binomial::Categorical:Multinomial*

5. **Nearest Neighbor** -- do scaling before fitting the data , good for small dataset.
6. **Support vector classifier**
7. **Gaussian classififer**
8. **Decision Tree**
9. **Random forest**
10. **Ada boost**
11. **Neural Net**
12. **QDA**



## Model Performance

| Model | Accuracy(%) |
| :---: | :---: |
| Logistic Regression | 80 |
| SGD Classifier | 79 |
| Logistic Regression CV | 80 |
| Multinomial NB | 76 |
| KNeighbors Classifier | 79 |
| SVC | 81 |
| Decision Tree Classifier | 78 |
| Random Forest Classifier | 79 |
| AdaBoost Classifier | 81 |
| MLP Classifier | 81 |
| Quadratic Discriminant Analysis | 80 |




## Exploratory Data Analysis

1. Feature : Age

![image](https://user-images.githubusercontent.com/76867868/167090944-457b08b8-9f1b-4ee8-a5ce-9bf3a81689bd.png)
![image](https://user-images.githubusercontent.com/76867868/167091067-43ef5c15-293b-4e30-a64b-29eb5b12aa71.png)

2. Feature : hours-per-week

![image](https://user-images.githubusercontent.com/76867868/167091214-d451589e-ec91-4ec1-b39f-35eb51537cb1.png)
![image](https://user-images.githubusercontent.com/76867868/167091294-a4e29eba-973e-4822-9167-e0d33f115fe8.png)

3. Feature : Race

![race](https://user-images.githubusercontent.com/76867868/167092039-23bda1bb-2afb-45df-8cd3-4b5e1950f787.PNG)


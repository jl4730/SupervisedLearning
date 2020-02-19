# SupervisedLearning

Writeup can be found at medium: https://medium.com/@jl4730/supervised-learning-8d73b43c856c

## 1 Linear Regression
### 1.1 batch_graddesc.py
Contains Mini-Batch Gradient Descent 

### 1.2 sklearnLinearRegression.py
Contains linear regression using sklearn module

### 1.3 PolynomialRegression.py
Contains polynomial regression using sklearn module

### 1.4 lassoregularization.py
Contains lasso regression using sklearn module

## 2 Classification
### 2.1 perceptron.py
Implement the perceptron algorithm to separate the 1s and 0s

### 2.2 DecisionTreeClassifier
Implement decision tree algorithm

### 2.3 titanic_survival_exploration
Implement decision tree algorithm on titanic dataset

### 2.4 Bayesian_Inference.ipynb
Implement bayesian inference algorithm on spam identification

### 2.5 SVM.py
Contains SVM algorithm using sklearn module

### 2.6 Spam_&_Ensembles.ipynb
Implement ensemble method on spam identification

### 2.7 Learning_Curve.py
Using learning curves to determine if a model is overfitting or underfitting

### 2.8 Grid_Search.ipynb
Using grid search to find the best model

### 2.9 Diabetes Case Study.ipynb
Using grid search to find the best model

### 3.0 finding_donors.ipynb
This is the capstone for supervised learning section. In this project, you will apply supervised learning techniques and an analytical mind on data collected for the U.S. census to help CharityML (a fictitious charity organization) identify people most likely to donate to their cause. You will first explore the data to learn how the census data is recorded. Next, you will apply a series of transformations and preprocessing techniques to manipulate the data into a workable format. You will then evaluate several supervised learners of your choice on the data, and consider which is best suited for the solution. Afterwards, you will optimize the model you've selected and present it as your solution to CharityML. Finally, you will explore the chosen model and its predictions under the hood, to see just how well it's performing when considering the data it's given.
predicted selling price to your statistics.

#### Data
The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper *"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid",* by Ron Kohavi. You may find this paper [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf), with the original dataset hosted on [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income).

**Features**
- `age`: Age
- `workclass`: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
- `education_level`: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
- `education-num`: Number of educational years completed
- `marital-status`: Marital status (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
- `occupation`: Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
- `relationship`: Relationship Status (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
- `race`: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
- `sex`: Sex (Female, Male)
- `capital-gain`: Monetary Capital Gains
- `capital-loss`: Monetary Capital Losses
- `hours-per-week`: Average Hours Per Week Worked
- `native-country`: Native Country (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)

**Target Variable**
- `income`: Income Class (<=50K, >50K)




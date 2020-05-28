This project is built with local machine anaconda environment Jupyter Notebook.

The data used is Campus Recruitment data from Kaggle (https://www.kaggle.com/benroshan/factors-affecting-campus-placement/data#).

The idea is to train a machine to predict how likely a student can secure a employment placement.

The environment setup is with matplotlib, numpy, pandas, sklearn.

First, all non-integer parameters are converted into boolean values or dummies. Then a RandomForestClassifier from sklearn is used to fit the model.

A function predict_placement is created to give probability of how likely a student will be given a placement.

# Higgs Boson Machine Learning Project

Hello! This is the read.me for the Higgs Boson Machine Learning project by Haakon Melgaard Sveen, Haakon Skirstad Grini and Tor Magnus Naesset. In this project we are using different Machine Learning methods to correctly classify between decay by the Higgs Boson or just background. By setting up this project you can run the files and get a prediction score of 74,47%, and you could also modify methods to get a even better score.

### Setup:

Before starting this project it is extremely important that you have the .csv-files from this challenge in the same directory as the .py-files. These files can be found on https://www.kaggle.com/c/higgs-boson/data. Also make sure you have the numpy installed on your computer.

### Content:

There are X different python files in this repository. 
Implementations.py covers the six different machine learning methods that was required to make during this project, in addtition to Gradient Descent and Stochastic Gradient Descent.

Computation.py does a lot of simple computations, like computing gradients, errors and losses that are used in implementations.py.

Run.py runs the whole project, from loading in the data to create a new csv-file with new predictions.

Cleaning.py contains the methods used for cleaning the data.

Validation.py contains the cross-validation methods we used, demos of these and the way we implemented the 5-fold cross validation used for result.

Helpers.py contains helper functions provided to this project, and also these additional helpers from the ML-labs:
A function for standardizing
Function for splitting data 
Batch iteration function for the stochastic gradient descent
Function for building a polynomial
Function for building the model data.

Not all of them is used for this project, but can be for further training of the data.


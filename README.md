# Detecting-Parkinson-s-Disease
Hey everybody, this is a Machine Learning project that is aimed to detect Parkinson's Disease


# Objective
The objective of the project is to detect Parkinson's Disease accurately in an individual

# What is Parkinson's Disease?
Parkinson’s disease is a progressive disorder of the central nervous system affecting movement and inducing tremors and stiffness. It has 5 stages to it and affects more than 1 million individuals every year in India. This is chronic and has no cure yet. It is a neurodegenerative disorder affecting dopamine-producing neurons in the brain.

# What is XGBoost?
XGBoost is a new Machine Learning algorithm designed with speed and performance in mind. XGBoost stands for extreme Gradient Boosting and is based on decision trees. In this project, we will import the XGBClassifier from the xgboost library; this is an implementation of the scikit-learn API for XGBoost classification.

# Python libraries being used
1. Scikit-learn 
2. Pandas
3. Numpy
4. XGBoost-- We build a model using the XBGClassifier

# Prerequisites and Environment
--> Any Integrated Development Environment such as Pycharm CE or VS Code 
--> Install the necessary modules or libraries using python package manager PIP 
--> Install a Extension or Application called JupyterLab, If you are using VS Code IDE, You can install JupyterLab extension from the store for free.


# Steps to implement and detect parkinson disease
--> Create a file with the extension '.ipynb'

1. Import all necessary modules and functions
2. Read the data in a dataframe 
3. Extract the features and labels from the Dataframe/Dataset. 
    Note: Features are all columns except 'Status' and labels are those in 'Status' columns
4. The ‘status’ column has values 0 and 1 as labels
5. Initialize a MinMaxScaler and scale the features to between -1 and 1 to normalize them. 
  The MinMaxScaler transforms features by scaling them to a given range. The fit_transform() method fits to the data and then transforms it. We don’t         need to scale the labels.
6. Now, split the dataset into training and testing sets keeping 20% of the data for testing.
7. Initialize an XGBClassifier and train the model. This classifies using eXtreme Gradient Boosting- using gradient boosting algorithms for modern data science problems. It falls under the category of Ensemble Learning in ML, where we train and predict using many models to produce one superior output.
8. Finally, generate y_pred (predicted values for x_test) and calculate the accuracy for the model. Print it out.

# Output Screenshot 
<img width="1440" alt="Screenshot 2022-12-07 at 2 35 29 PM" src="https://user-images.githubusercontent.com/108233235/206135812-d5599ae9-1ea2-4948-bd90-7b2c55b3c5de.png">

# Contributions
Feel free to contribute in any way you wish to.

Steps to follow to contribute:

1. Fork the repository

2. You can clone the project directly using Github Desktop or the link to your local directory

3. Create a new branch and make changes to it.

4. Raise an issue mentioning the changes you plan to make, discuss and upon approval

5. Open a pull request mentioning the Issue Number it closes/resolves.

Thank you!🙌

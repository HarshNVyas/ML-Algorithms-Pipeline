# ML-Algorithms-Pipeline

## Overview
This GitHub repository, named 'ML-Algorithms-Pipeline,' is a comprehensive collection of Python scripts and Jupyter notebooks designed for Machine Learning (ML) practitioners. The repository encompasses three main files, each addressing specific aspects of the ML workflow, along with additional folders containing datasets, models, and extra resources.

## Repository Structure
* Folders:

  1. datasets: Contains datasets generated as part of the three main files.
  2. Models: Includes machine learning models created in conjunction with the three files.
  3. Extra Resources: Provides supplementary materials to enhance understanding and support the analysis within the repository.

* Files:

  1. Data_Preprocessing.ipynb:
  
    * Objective: This Jupyter notebook focuses on data preprocessing using Python 3 within Google Colab. It employs various libraries, including NumPy, Pandas, Sklearn, matplotlib, and seaborn.
    * Key Steps:
      * Data loading from diverse sources (CSV, Excel, databases, web APIs) using Pandas.
      * Exploratory Data Analysis (EDA) for initial dataset understanding through summary statistics and visualizations.
      * Handling missing data, employing techniques to fill in values.
      * Feature engineering to create new features, transform existing ones, and encode categorical variables.
      * Data scaling to standardize or normalize numerical features.
      * Data splitting into training and testing sets for effective model performance evaluation.
     

  2. Supervised_and_Unsupervised_Modelling_and_Evaluation.ipynb:
  
    * Objective: This notebook covers supervised and unsupervised machine learning problems, including classification, regression, clustering, and association. It also demonstrates the use of Sklearn's Pipeline method and compares Joblib and pickle for model saving.
    * Key Sections:
      * Introduction
      * Supervised Learning:
        * Classification using various algorithms (Logistic Regression, Decision Tree, Random Forest, SVM, K-Nearest Neighbours, Naive Bayes).
        * Regression with algorithms like Linear Regression, Support Vector Regressor, and Random Forest Regressor.
        * Hyperparameter tuning using manual testing, RandimizedSearchCV, and GridSearchCV.
      * Unsupervised Learning:
        * Clustering methods such as K-Means, Hierarchical Clustering, and DBSCAN.
        * Association using the Apriori Algorithm.
      * Saving Models using Pickle and Joblib.
     
    
  3. Canadian_Immigration_Data_Semi_Supervised_Learning.ipynb:
  
    * Objective: This notebook focuses on a semi-supervised learning project using regression models to substitute missing data. It incorporates unsupervised learning techniques for clustering Canadian immigration data.
    * Additional Components:
      * Flowchart for implementation provided in 'Extra Resources' folder.
      * Visualizations made in Tableau.
      * Poster created using PowerPoint presentation.
## Usage Guidelines
  * The scripts and notebooks are written in Python 3 and are compatible with Google Colab and Jupyter environments.
  * Ensure the installation of required libraries: NumPy, Pandas, Scikit-learn, Matplotlib, seaborn.
  * Follow the sequence of files for a structured understanding of data preprocessing, supervised, and unsupervised learning.


Feel free to explore, contribute, and provide feedback for continual improvement!

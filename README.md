# bioinformatics project
RNA Structural Motif Classification using Machine Learning
This project presents an end to end Machine Learning framework for analyzing and classifying RNA structural motifs using large scale biological data. The dataset contains over 200,000 RNA motif samples across 25 structural classes with 84 continuous structural and torsion-angle features.
The project explores multiple traditional Machine Learning algorithms and a Deep Learning model to identify the most effective approach for multi class RNA motif classification. The workflow includes data preprocessing, exploratory data analysis, feature scaling, model training, hyperparameter tuning, performance evaluation, and visualization. 
Features
Data preprocessing and missing value handling
Exploratory Data Analysis (EDA) with plots and heatmaps
Multi-class classification of RNA motifs
Implementation of:
Logistic Regression
Random Forest
Support Vector Machine (SVM)
Multilayer Perceptron (MLP)
Hyperparameter tuning using GridSearchCV and RandomizedSearchCV
Model evaluation using Accuracy, Precision, Recall, F1-score, ROC-AUC, and Confusion Matrix
Learning curve analysis for underfitting vs overfitting detection
Feature importance analysis using Random Forest
Prototype deployment using Streamlit
Technologies Used
Python
Pandas
NumPy
Scikit learn
Matplotlib
Seaborn
Streamlit
Results
Among all evaluated models, Random Forest achieved the best performance with approximately 94% classification accuracy on the test dataset, demonstrating strong capability in learning complex non-linear RNA structural patterns.
Applications
This project demonstrates the application of Machine Learning in bioinformatics and RNA structural analysis, with potential applications in:
RNA structure prediction
Molecular biology research
Computational biology
Drug discovery and genomics research


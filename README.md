# DecisionTree
Implementation of Decision Trees for classification tasks

Decision Trees are implemented without using python in-built scikit library.
The implemented decision tree algorithm is applied to Wisconsin Diagnostic Breast Cancer Dataset.
The dataset has several features that represent the chracteristics of the breast cell nuclei. The target variable has two classes - M and B

In the DecisionTree.ipynb file, 
1. Decision Tree is implememted with chi-square pruning as an additional parameter (ON - pruning, OFF - no pruning)
2. The implemented algorithm is applied to WDBC dataset
   a. Exploratory Data Analysis
   b. Pre-processing
   c. Decision Tree with and without pruning
   d. Validation on dev data
   e. Performance evaluation using precision, recall, accuracy and f1-score. 

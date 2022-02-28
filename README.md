# ML project 2021-2022
### The purpose of the model is to predict whether an employee will look for a new job.

#### * The content of the project (docx files) is written in the Hebrew language. *

 ## Part A - 
 
 #### 1. Data collection and Sensing.
 #### 2. Dataset Creation.
    A. Exploratory data analysis.
    B. Dataset Creation Steps.
      1. Pre-processing.
      2. Segmentation.
      3. Feature Extraction (Corrections are attached in Part B).
      4. Feature Representation.
      5. Feature Selection (Corrections are attached in Part B).
      6. Dimensionality Reduction (PCA).
#### 3. Selection of the Validation k-fold (k=10) method.

## Part B - 

#### 1. Training the model 
    A. Decision Tree - using Hyperparameter tuning, Grid Search (max_depth=5, criterion=entropy, splitter=best).
    B. Artificial Neural Networks - (activation=tanh, max_iter=450, hidden_layer_sizes=(13,13)).
    C. SVM - using Hyperparameter tuning, Grid Search (C=35, loss=squared_hinge).
    D. Unsupervised Learning - Clustering, K-medoids algorithm - we have 2 classes in our data, 
     Clustering on our data gives us best of 5 classes by Silhouette Coefficient and Davies-Bouldin Index.
     
#### 2. Evaluation - 
    A. Decision Tree - accuracy: Test set - 0.798 +/- 0.002, Validation set - 0.788 +/- 0.013.
                               
    B. ANN-MLP -       accuracy: Test set - 0.805 +/- 0.003, Validation set - 0.789 +/- 0.016.
                               
    C. SVM -           accuracy: Test set - 0.748 +/- 0.017, Validation set - 0.746 +/- 0.029.
  
#### 3. Improvements.



### Thank you for reading, I am open for any quation.

  
  




    

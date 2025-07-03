# SUPPORT-VECTOR-MACHINE

# NAME : MURARI YAMINI

### DESCRIPTION :
This is a simple but powerful machine learning task where we use Support Vector Machines (SVMs) to figure out whether a breast tumor is benign (not dangerous) or malignant (cancerous) using a real medical dataset.

We’ll walk through:

- loading and cleaning the data

- visualizing patterns in 2D

- training two types of SVM models (linear and RBF)

- making predictions

- improving accuracy with tuning

### DATASET USED :breast cancer dataset

### Tools Used
- python

- pandas, numpy, matplotlib

- scikit-learn for modeling, scaling, PCA, and tuning

  ### STEPS INVOLVED :
 - load the dataset from a CSV file

- Preprocess it (drop unnecessary columns, encode diagnosis)

- Scale all features to the same range using StandardScaler

- apply PCA to reduce the data to 2 dimensions (just for visualization)

- Split the data into training and test sets

- train two SVM classifiers:

- one with a linear kernel

- one with an RBF (non-linear) kernel

- visualize how both models draw decision boundaries

- tune hyperparameters (like C and gamma) using GridSearchCV

- evaluate the best model on the test data

  ### OUTPUT :
  

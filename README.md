# Breast-Cancer-Classification
Compared the performance of Naïve Bayes and Logistic Regression classifiers for predicting breast cancer data using appropriate metrics for validation.

A breast cancer dataset was given to perform a classification problem to predict whether a certain patient has cancer or not. 

The features in the dataset are listed below:

* **Cl.thickness**: Clump Thickness
* **Cell.size**: Uniformity of Cell Size
* **Cell.shape**: Uniformity of Cell Shape
* **Marg.adhesion**: Marginal Adhesion
* **Epith.c.size**: Single Epithelial Cell Size
* **Bare.nuclei**: Bare Nuclei
* **Bl.cromatin**: Bland Chromatin
* **Normal.nucleoli**: Normal Nucleoli
* **Mitoses**: Mitoses

The label to use for our prediction is:

* **Class**: Class (Benign or Malignant)

Moreover, the classifaction models to be used in this problem are **Logistic Regression** and **Naïve Bayes**.

1. **Logistic Regression**: Logistic Regression is a supervised-learning techniques, which is mostly used in classification problems. The model predict the variables based on a logistic function which classifiy if a certain variable is above or below a specific threshold. [9]
    - There are three types of Logistic Regression: 
        1. **Binary**: Predicting 2 possible outcomes.
        2. **Multinomial**: Predicting 3 or more possible outcomes without order.
        3. **Ordinal**: Predicting 3 or more possible outcomes with order.


2. **Naïve Bayes**: Naïve Bayes is a supervised-learning technique, which is also used in classifictaion problems but based on probabilty. Using Bayes Theorem, the probabilty of certain features is calculated to predict the output. [8]
    - There are three types of Naïve Bayes Classifier: 
        1. **Multinomial**: Used mostly in text classification NLP where features follow a Multinomial Distribution.
        2. **Bernoulli**: Features follow a Bernoulli Distribution, in which features are binary values.
        3. **Gaussian**: Features follow a Normal Distribution.
        
Thereofore, in the following task, **Binary Logistic Regression** and **Gaussian Naïve Bayes classification** are used.

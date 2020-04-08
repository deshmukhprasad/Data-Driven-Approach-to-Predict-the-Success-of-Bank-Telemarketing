# Data-Driven-Approach-to-Predict-the-Success-of-Bank-Telemarketing
The project consists of data driven approach to predict whether the customer will subscribe to the scheme using telemarketing based on the data of customer

## **Logistic Regression** 
Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable. In regression analysis, logistic regression is estimating the parameters of a logistic model.Logistic regression is named for the function used at the core of the method, the logistic function.Logistic regression uses an equation as the representation, very much like linear regression.

**Types of Logistic Regression**

**1. Binary Logistic Regression**
The categorical response has only two 2 possible outcomes. Example: Spam or Not.

**2. Multinomial Logistic Regression**
Three or more categories without ordering. Example: Predicting which food is preferred more (Veg, Non-Veg, Vegan).

**3. Ordinal Logistic Regression**
Three or more categories with ordering. Example: Movie rating from 1 to 5.

In order to map predicted values to probabilities, we use the Sigmoid function. The function maps any real value into another value between 0 and 1. In machine learning, we use sigmoid to map predictions to probabilities.

![SIGMOID](https://user-images.githubusercontent.com/36560636/78674890-ec068580-7901-11ea-87fd-73fe37d42d1d.PNG)

# The data-set used contains the following parameters:

Input variables:
Age (numeric)
Job: career type (categorical: 'admin.', 'blue-collar', 'entrepreneur', 'housemaid', 'management', 'retired', 'self-employed', 'services', 'student', 'technician', 'unemployed')
Marital_Status: marital status (categorical: 'divorced', 'married', 'single'; note: 'divorced' means divorced or widowed)
Education: (categorical: 'PrimaryEducation', 'ProfessionalEducation', 'SecondaryEducation', 'TertiaryEducation')
Default_Credit: has a credit in default? (binary: 'yes', 'no')
Housing_Loan: has a home loan? (binary: 'yes', 'no')
Personal_Loan: has a personal loan? (binary: 'yes', 'no')
Output variable (desired target):
Subscribed - has the client subscribed a long-term deposit? (binary: 'yes', 'no')

# Visualizations in form of various graphs is provided as per the data from the dataset.

![download](https://user-images.githubusercontent.com/36560636/78676587-430d5a00-7904-11ea-8d45-59e80bc801a3.png)

![download (1)](https://user-images.githubusercontent.com/36560636/78676796-8c5da980-7904-11ea-9489-8b7cea9abe6a.png)

![download (2)](https://user-images.githubusercontent.com/36560636/78676843-a1d2d380-7904-11ea-8478-8c771a36a231.png)

## **Confusion Matrix** 

A confusion matrix is a table that is often used to describe the performance of a classification model (or “classifier”) on a set of test data for which the true values are known. It allows the visualization of the performance of an algorithm.
It allows easy identification of confusion between classes e.g. one class is commonly mislabeled as the other. Most performance measures are computed from the confusion matrix.

![Confusion_Matrix1_1](https://user-images.githubusercontent.com/36560636/78677074-ec545000-7904-11ea-9ed2-d12fb90c1480.png)

Here,

- Class 1 : Positive
- Class 2 : Negative

Definition of the Terms:

- Positive (P) : Observation is positive (for example: is an apple).
- Negative (N) : Observation is not positive (for example: is not an apple).
- True Positive (TP) : Observation is positive, and is predicted to be positive.
- False Negative (FN) : Observation is positive, but is predicted negative.
- True Negative (TN) : Observation is negative, and is predicted to be negative.
- False Positive (FP) : Observation is negative, but is predicted positive.
 
# **Classification Rate/Accuracy**
Classification Rate or Accuracy is given by the relation:

![Confusion_Matrix2_2](https://user-images.githubusercontent.com/36560636/78678153-368a0100-7906-11ea-9bfb-a289e5d827f9.png)

# Sampling techniques for making balanced samples from imbalanced dataset

## Introduction

In order to create different samples from the credit catd dataset for this project, we must utilise a variety of sampling approaches. The next step is to accurately classify a variety of samples using a variety of classification models, and then compare the accuracy results in the form of an accuracy matrix. 31 features and 772 observations are included in the provided dataset. This dataset for binary classification has 763 0s and just 9 1s. We must thus employ efficient sampling methods.

## Balancing the dataset

We must first equalise the ones and zeroes. Both oversampling and undersampling are options for it. I utilised oversampling for the aforementioned dataset, which produced a new dataset with an equal number of zeros and ones.

## Sampling Techniques

5 Sampling techniques were used on the balanced dataset which are:-

1.Random Sampling

2.Systematic Sampling

3.Stratified Sampling

4.SMOTE(Synthetic Minority Oversampling Technique) with random sampling

5.Convinience Sampling

## Model Training

After appling the sampling techniques, the following 5 Machine Learning models are trained on the 5 samples obtained above-

1.Logistic Regression

2.Decision Tree

3.SVC Classifier

4.Random Forest Classifier

5.Naive Bayes Classifier

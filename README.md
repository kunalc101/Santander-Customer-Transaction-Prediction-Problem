# Santander Customer Transaction Prediction Problem

## Business Context:

At Santander, mission is to help people and businesses prosper. We are always looking for ways to help our customers understand their financial health and identify which products and services might help them achieve their monetary goals.

Our data science team is continually challenging our machine learning algorithms, working with the global data science community to make sure we can more accurately identify new ways to solve our most common challenge, binary classification problems such as: is a customer satisfied? Will a customer buy this product? Can a customer pay this loan?

## Problem Statement:

In this challenge, we need to identify which customers will make a specific transaction in the future, irrespective of the amount of money transacted.

## Summary and Recommendations:

Santander Customer Transaction Prediction problem has a highly anonymized and redacted dataset most likely in favour of protecting the privacy of users involved. Also, there is almost no correlation between various variables and there is no central important set of features in this dataset. Undersampling/over-sampling and feature engineering was done to deal with the class imbalance problem and to add uniqueness to the important features in training and test data.

Finally, considering the overall performance of 6 different classification models, the Light GBM model  shows the best performance in terms of ROC-AUC and PR AUC which is the benchmarking classification metric for this project. This project will help Santander bank to make better policy decisions regarding which of their customers makes certain specific choices regarding the nature of financial transaction that they are willing or unwilling to engage in.

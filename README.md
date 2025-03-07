
# Introduction

## Introduction
In this section, you'll learn about some ways to make linear models more complex to account for more complicated relationships in a dataset. Before diving in too deep, here is a roadmap for what you will be covering in this section.

## Objectives
You will be able to:
* Create models to account for non-linear relationships
* Critically assess what features should be included in a model

##  Extensions to Linear Models

Unfortunately, not every continuous variable can be predicted effectively using a straight line (a linear model). Imagine the relationship between your 5k time as a runner and how many hours a week you train. At the very least the improvements in your time are going to trail off with additional training (going from 0 -> 10 hrs training a week is going to have way more impact than going from 60 -> 70 hrs). And the chances are that at some point in time, you'll overtrain and additional training will actually degrade your performance. You could certainly model the relationship between weekly training hours and 5k time with a straight line, but for some values of weekly training time, the accuracy of the prediction would probably be extremely low.

In this section, you'll be introduced to a number of concepts to help you to make predictions where there is not a linear relationship between the predictor and target variables.

### Interactions

You'll start by introducing the concept of interactions - where two or more variables interact in a non-additive manner when affecting a third variable. Then you'll look at why they are important and how to account for them.

### Polynomial Regression

You'll then implement higher-order equations for solving regressions. A linear expression can be described by an equation in the form of y = mx + b. A polynomial expression brings in higher powers of x (squared, cubed, etc). By allowing for equations containing higher-order terms you may be able to better fit a curve to your data set, better predicting future values.

### Bias-Variance Tradeoff

While polynomial regression can improve the accuracy of your models, they also exacerbate the risk of over-fitting the data, making your model extremely accurate for the training set but completely inaccurate for any future data points the model wasn't trained on. You'll take some time to look at the concept of bias-variance trade-off and how it relates to underfitting and overfitting data sets.

### Ridge and Lasso Regression

Next up, you'll learn about Ridge and Lasso regressions - two techniques that penalize more complex models to reduce overfitting.

### AIC and BIC

Finally, you'll learn about AIC and BIC - two tools for comparing potential models to help better select between them. 


## Summary

It's time to start learning about extensions to linear models!

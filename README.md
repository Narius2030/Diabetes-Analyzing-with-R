## Table of contents
* [General Information](#general-info)
* [Problem Solving](#business-purposes)
* [Technology](#design-models)

## General Information
> Overall of dataset: women's medical and demographic data to predict diabetes
This dataset contains information on 769 women and includes many health-related attributes. Here is a brief overview of the columns:

* Pregnancy: The number of times a woman has been pregnant.
* Glucose: The concentration of glucose in a woman's plasma.
* Blood pressure: Measure blood pressure.
* Skin thickness: The thickness of the skin folds in the triceps.
* Insulin: Insulin concentration in the blood.
* BMI (Body Mass Index): A measure of body fat based on height and weight.
* Diabetes pedigree function: A function that shows the likelihood of developing diabetes based on family history.
* Age: Age of the woman.
* Outcome: The target variable indicates whether the woman has diabetes (1 for diabetics, 0 for non-diabetics).

## Problem Solving
> Exploring the dataset and Pre-processing
* Describing the most overall vision for reader to comprehend what exactly this dataset's structure is
* Utilizing some legible visualization techniques for plotting out the significant features of dataset
* Identifying any abnormal things in dataset, such as null/nan data points or outliers, which will affect incorrectly in analyzing process

> Establishing the prediction model with Logistic Regression and Decision Tree
* This problem means to forecast whether the patient got diabetes or not by lying the feature attributes, which have strong correlations with the Outcome variables
* Observing generally the dataset to define which attributes are not necessary for these problems. Then, we will remove them before construct the machine learning models
* Comparing the performance and accuracy of the two models and making a conclusion which one is better

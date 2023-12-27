## Table of contents
* [General Information](#general-information)
* [Problem Solving](#problem-solving)
* [Technology](#technology)

## General Information
> ### Referencing to the published project on Rpubs: [diabetes-analyzing-ml](https://rpubs.com/Narius2030/diabetes-analyzing-ml)
### Overall of dataset: women's medical and demographic data to predict diabetes

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
> ### 👨‍🏫 Exploring the dataset and Pre-processing
* Describing the most overall vision for reader to comprehend what exactly this dataset's structure is
* Utilizing some legible visualization techniques for plotting out the significant features of dataset
* Identifying any abnormal things in dataset, such as null/nan data points or outliers, which will affect incorrectly in analyzing process

>  ### 📊 Establishing the prediction model with Logistic Regression and Decision Tree
* This problem means to forecast whether the patient got diabetes or not by lying the feature attributes, which have strong correlations with the Outcome variables
* Observing generally the dataset to define which attributes are not necessary for these problems. Then, we will remove them before construct the machine learning models
* Comparing the performance and accuracy of the two models and making a conclusion which one is better

> ### 🗂 Classifying the categories of mass using Random Forest model
* The problem serves for identifying the mass situation of patient such as underweight, normal, overweight and obese. It will be helpful for doctors can keep track the health of patient having a probability of diabetes
* Observing generally the dataset to define which attributes are not necessary for these problems. Then, we will remove them before construct the models
* Having some fine-tuning tasks for selecting the best values' parameters. Then, we can build as the best model as possible base on these fine-tuned parameters

> ### 🕵️‍♀️ Hypothesis validation using T-Test technique
* Using One-sample T-test, hypothesis that an average BMI (Body Mass Index) of 34 is susceptible to diabetes
* Using Independent Samples T-test, The hypothesis that body fat (BMI) does not affect whether or not there is disease
* Using One-sample T-test, hypothesis that the age also affects whether a person has diabetes

## Technology
* Environment: [Rstudio](https://posit.co/download/rstudio-desktop/), [R interpreter](https://cran.rstudio.com/)
* Display mode: R-Markdown or R-Notebook
* Packages: 
  + [glm](https://www.rdocumentation.org/packages/stats/versions/3.6.2/topics/glm) for logistic regression
  + [rpart](https://www.rdocumentation.org/packages/rpart/versions/4.1.23/topics/rpart) for decision tree model
  + [randomForest](https://www.rdocumentation.org/packages/randomForest/versions/4.7-1.1/topics/randomForest) for random forest models, 

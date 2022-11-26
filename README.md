# data_science_project_2022
## Background
Despite the fact that most of our planet is covered with water, not more than 3 % of this amount is fresh. To make sure that the water is safe to drink the Estonian Health Board has been measuring its quality in more than thousand water stations across the country thereby making sure that every citizen will get the freshest water right from their tap.
To bring water quality measurement to the next level and automate working process of Estonian water inspectors, we would like to invent predictive water quality model that would enable us to prioritize the tests or react proactively to the deterioration of the water conditions. Therefore, enhancing the role of scientific and data-driven approach on a governmental level.

## Goal
The goal of this competition is to create a model that predicts the water quality in Estonian water stations based on the government’s open data of the previous measurements.

## Dataset Description
### Overview
The data has been split into two groups:

Training set (train.csv)
Test set (test.csv)

The training set should be used to build your machine learning models. The training set includes both the features and the result variable (compliance_2021).

If we succeed in building a good machine learning model, then we have created a model that enables to predict the quality of the next test based on the metrics of previous tests.

The test set should be used to see how well our model performs on unseen data. The test set doesn’t include the result variable. It is our job to predict it using the model we built on the training data!

It include sample_submission.csv - an example of what the submission file should look like (the predictions in the sample file are picked randomly).

### Features
The features include various numeric metrics (e.g. color, smell, ph-level, coli-type bacteria) from previous water tests that are used by the inspectors to define whether the quality is compliant with the regulation. For each water station, you have information about the test results of the years 2019 and 2020. The corresponding year number is added at the end of each variable name. In addition, you have the information about the compliance of the station in 2019 (compliance_2019) and 2020 (compliance_2020). The result variable is compliance_2021.

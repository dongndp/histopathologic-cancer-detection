# Week3: CNN: Histopathologic Cancer Detection

### Project Overview

In this assignment, we're going to participate in the Kaggle [Histopathologic Cancer Detection](https://www.kaggle.com/c/histopathologic-cancer-detection) Challenge. We'll build deep learning models to identify metastatic tissue in histopathologic scans of lymph node sections using Convolutional Neural Network (CNN) algorithm. The models are evaluated on area under the ROC curve between the predicted probability and the observed target. We will not aim to achieve the highest possible score. Instead, this project demontrates how to apply CNN model and prevent overfitting using batch normalization, dropout, and regularization techniques.

### About the dataset

We will be using the Kaggle [Histopathologic Cancer Detection](https://www.kaggle.com/c/histopathologic-cancer-detection) dataset. The dataset is provided subjected to [Kaggle Competition Rules](https://www.kaggle.com/competitions/histopathologic-cancer-detection/rules#7-competition-data).

Here is the dataset description from Kaggle: "In this dataset, you are provided with a large number of small pathology images to classify. Files are named with an image id. The train_labels.csv file provides the ground truth for the images in the train folder. You are predicting the labels for the images in the test folder. A positive label indicates that the center 32x32px region of a patch contains at least one pixel of tumor tissue. Tumor tissue in the outer region of the patch does not influence the label. This outer region is provided to enable fully-convolutional models that do not use zero-padding, to ensure consistent behavior when applied to a whole-slide image."

This dataset consists of:

- File train_labels.csv: provides the ground truth for the images in the train folder
- File sample_submission.csv: provides the sample of submission
- Folder train/: images for traning
- Folder test/:  images for testing

Summary of Tasks:
- Loading dataset
- Exploratory Data Analysis: 
    - Explore the dataset, perform data cleaning, data analysis, and image processing.
- Build and test models: 
    - Build, evaluate, and compare model's performances. 
- Conclusions: 
    - Summarize and discuss the results.

# DA2-Project-Group-16
Plant Traits 2024 Kaggle Competition

## Table of Contents

1. [About the Project](#about-the-project)
    - [Getting Started](#getting-started)
      - [Project Dependencies](#project-dependencies)
2. [Authors](#authors)
   

## About the Project
A full report to this project can be found in [Final Project](https://github.com/henryvanboskirk/DA2-Project-Group-16/blob/main/DA2%20Project%20Report%20(2).docm)

## Getting started
To utilize this model, in addition to the files in this repository you will need the dataset which can be accessed via the competition page via [kaggle](https://www.kaggle.com/competitions/planttraits2024/overview) under the data tab.

The files associated with our submission are 

- train_images - The folder with the training images (.jpeg)
* train.csv - The labels and the ancillary data (satellite data, soil data, climate data etc.) for each training image
* test_images - The folder with the test images (.jpeg) that shall be used to create the predictions for the submission.
* test.csv - The ancillary data (satellite data, soil data, climate data etc.) for each test image
* target_name_meta.csv - full names of the traits obtained from the TRY database. This is important to understand what all traits are we predicting
* sample_submission.csv - a sample submission file in the correct format

## Project Dependencies
Below is a list of libraries required to run this project. Ensure that you install these specific versions to maintain compatibility with the project's code.

* torch

```bash
pip install torch

* torchvision

* sklearn

* matplotlib

## Authors
* Henry Van Boskirk
* Zachary Debler
* Ryan Gilbert

# Melanoma Detection Using CNN

## Table of Contents
* [Problem Statement](#problem-statement)
* [Data Analysis](#data-analysis)
* [Model Creation](#model-creation)
* [Augmentation](#augmentation)
* [Conclusion](#conclusion)
* [Technologies Used](#technologies-used)
* [Glossary](#glossary)
* [Team](#team)

## Problem Statement

Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Data Analysis

- Read the data form google drive.
    - Unzip the file to fetch images
    - Create train and validation data sets
    - Visualize the data
 
## Model Creation
- create the CNN model
- Compile it using Adam Optimiser
- Fit the model with 20 epoch

## Augmentation
- Use Augmentor to eliminate the imbalances
- Then recreate the model and try to fit it using 30 epochs

## Conclusion
- The CNN model is a good fit after using Augmentor.
- Model loss reducedx and accuracy improved after 30 epochs


## Technologies Used
- [Python - Version 3.12.1](https://www.python.org/downloads/release/python-3121/)
- [pandas - Version 2.1.4](https://github.com/pandas-dev/pandas)
- [matplotlib - Version 3.8.2](https://github.com/matplotlib)
- [seaborn - Version 0.13.1](https://github.com/seaborn)
- [TensorFlow - Version v2.16.1](https://www.tensorflow.org/install/pip)
- [Jupyter Notebook - Version 7.0.6]()
- [JupyterLab - Version 4.0.9]()

## Glossary
- CNN Model

## Team
* [Prachi Goliwadekar]

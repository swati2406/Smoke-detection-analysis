# Smoke-detection-analysis
This project focuses on detecting smoke in detectors using classification techniques.

![dataset-cover](https://user-images.githubusercontent.com/71493898/232565335-ca7a80df-8707-4219-a076-ef9a7486a71a.jpg)

# 1. Business Problem
A smoke detector is a device that senses smoke, typically an indicator of fire. Smoke detectors are usually housed in plastic enclosures, naturally shaped like a disk about 150 millimeters (6 in) in diameter and 25 millimeters (1 in) thick, but shape and size vary.

Types of Smoke Detectors:-

### i. Photoelectric Smoke Detector
A photoelectric smoke detector contains a source of infrared, visible, or ultraviolet light, a lens, and a photoelectric receiver. In some types, the light emitted by the light source passes through the air being tested and reaches the photosensor. The received light intensity will be reduced due to scattering from particles of smoke, air-borne dust, or other substances; the circuitry detects the light intensity and generates an alarm if it is below a specified threshold, potentially due to smoke. Such detectors are also known as optical detectors.

### ii. Ionization Smoke Detector
An ionization smoke detector uses a radioisotope to ionize the air. If smoke particles enter the open chamber, some ions attach to the particles and cannot carry the current. An electronic circuit detects a current difference between the open and sealed chambers and sounds the alarm.

Any smoke detector should sense smoke so that lives and resources are saved and the loss minimized as much as possible.

# 2. Solution

My solution to this business problem is to build a classification model to predict whether it is smoke.
## Gathering Data
The dataset is taken from https://www.kaggle.com/datasets/deepcontractor/smoke-detection-dataset.
## Data Preparation
This section will study the nature of the data we work with. The characteristics, format, and quality of data are understood.
A better understanding of data leads to an effective outcome. In this, I will perform statistical calculations and find correlations, general trends, and outliers.
## Data wrangling
In this section, I will preprocess the data for analysis.

i. Missing values will be deleted or imputed </br>
ii. Outliers will be replaced and </br>
iii. Invalid data will be removed </br>
## Data Analysis
This section aims to analyze the data using various analytical techniques and review the outcome. It starts with the determination of the type of problems, where we select the machine learning techniques such as Classification, Regression etc.
## Building model
This section trains and tests various classification models on data, split by hold-out cross-validation technique.
## Hyperparameter Tuning
The selected model is optimized by hyperparameter tuning to provide the best result for unseen data. 
## Conclusions
The model is tested on unseen data. In addition, some business questions are answered to check model usability in real-world scenarios.



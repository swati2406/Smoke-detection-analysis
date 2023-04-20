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
iv. Duplicate data will be dropped </br>
v. Imbalanced dataset will be balanced </br>
## Data Analysis
This section aims to analyze the data using various analytical techniques and review the outcome. It starts with the determination of the type of problems, where we select the machine learning techniques such as Classification, Regression etc.
## Building model
This section trains and tests various classification models on data, split by hold-out cross-validation technique.
## Hyperparameter Tuning
The selected model is optimized by hyperparameter tuning to provide the best result for unseen data. 
## Conclusions
I build multiple classification models to provide a solution for the problem statement. 
1. On evaluating the performance of all models, KNN, Decision Tree, and Random Forest performed better than Logistic Regression.</br>

### Logistic Regression
![image](https://user-images.githubusercontent.com/71493898/233459800-dfe6749b-1bfe-427c-a986-77e02dffc596.png)
### KNN
![image](https://user-images.githubusercontent.com/71493898/233460969-421b52a1-2f35-455f-80a0-abadc3935b09.png)
### Decision Tree
![DT](https://user-images.githubusercontent.com/71493898/233461416-e5e6d3b6-cde5-44ae-9735-ad1872d4482f.png)
### Random Forest
![RF](https://user-images.githubusercontent.com/71493898/233461467-7a70fcec-b54b-4e6f-b56e-9bac7d0b5cbf.png)

### ROC
![image](https://user-images.githubusercontent.com/71493898/233461626-d198d7ea-635e-4b3d-8e7e-c15492e48308.png)


2. For a problem statement like this, it is essential to have minimum false negatives (i.e., Type II error) so that no casualties occurred.
Looking at the confusion matrix of individual models, I chose Random Forest Classifier as it was able to detect smoke accurately. </br>
![image](https://user-images.githubusercontent.com/71493898/233461867-67efd129-5772-4c79-86ed-103635f6f08f.png)
![image](https://user-images.githubusercontent.com/71493898/233461909-20a8a0b6-ba6b-4a10-a455-0a1afba1cf41.png)
![image](https://user-images.githubusercontent.com/71493898/233461954-f7c57bd2-5a4a-4fc8-9aa3-199e5d0c280e.png)




# AAI-521-Final-Project

# HarvestGuard 
## Introduction
Agriculture is pivotal for global food supply, but diseases pose a significant threat, causing economic loss and contributing to hunger. HarvestGuard aims to address this challenge by developing a classification model using an Afrocentric dataset to accurately identify and categorize crop diseases based on annotated leaf images.

## Dataset
HarvestGuard utilizes the Crop Disease (Ghana) Dataset from the Responsible AI Lab, featuring annotated images of crops from Ghana. The dataset encompasses three crop types (tomato, pepper, and corn) and nine unique diseases. Bounding box coordinates in XML files or a label CSV file enable precise localization of diseased areas.

## Methods
Data Pre-Processing/EDA:
Image Size Analysis: Identified variations in image sizes, necessitating resizing before model input.

Class Distribution Analysis: Addressed class imbalance through merging similar classes and applying resampling techniques.

## Model Architecture
VGG16-Based Model: Utilizes a proven architecture for image classification tasks.

Two-Branch Structure: Features separate branches for bounding box regression and class label prediction.

## Purpose
HarvestGuard demonstrates the potential of Computer Vision in agricultural processes. While achieving commendable results, ongoing improvements, dataset curation, and scalability considerations are vital for addressing dynamic agricultural challenges. The project aims to contribute to sustainable AI solutions for advancing agricultural sciences.

## Contributors
Prachi Khana

Lauren Taylor

Ryan Laxamana

# Image-classification-Feature-Extraction-WeatherDataset

## Introduction
This project focuses on classifying weather conditions from images using advanced feature extraction techniques and machine learning models. Leveraging a custom weather dataset, the goal is to accurately categorize images into distinct weather classes, enhancing applications in meteorology, autonomous driving, and surveillance systems.

##Dataset
Source: Multi-class Weather Dataset (MWD)

Classes: Cloudy, Rain, Shine, Sunrise

Total Images: 1,125

Distribution:

Cloudy: 300

Rain: 250

Shine: 275

Sunrise: 300

## Feature Extraction
Utilized the img2vec_pytorch library to extract feature vectors from images using a pre-trained ResNet18 model. This approach captures high-level features, facilitating effective classification.

## Model Training
Algorithm: Random Forest

Training: Features extracted from images were used to train the Random Forest.

Evaluation Metrics
Accuracy: Achieved 97.8% on the test set.


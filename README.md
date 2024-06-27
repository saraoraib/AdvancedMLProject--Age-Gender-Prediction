# AdvancedMLProject--Age-Gender-Prediction
## Introduction
The aim of this project was to analyze a dataset of facial images to predict age and gender using a deep learning model. The dataset consists of images labeled with age and gender, extracted from the UTKFace dataset. The tasks involved exploratory data analysis, visualizing distributions, defining age groups, and finally, training a convolutional neural network (CNN) model to predict both age and gender.
## Discussion of Results
#### Data Analysis and Visualization
Dataset Characteristics: The dataset includes 23,708 images with corresponding age and gender labels.
Age Distribution: The most frequent age group observed was 21-30 years, with 7784 occurrences.
Gender Distribution: Males were slightly more represented than females, with 12,391 male images and 11,317 female images.
Image Visualization: Visualized random samples and age group-specific samples to understand the dataset's composition.
#### Model Training and Evaluation
Model Architecture: Designed a CNN model with convolutional layers for feature extraction followed by dense layers for classification.
Training Process: Trained the model for 30 epochs, optimizing for binary cross-entropy (gender prediction) and mean absolute error (age prediction).
Performance Metrics: Monitored training and validation accuracy and loss for both gender and age predictions.
Predictions: Demonstrated model predictions on sample images, showing both original and predicted gender and age values.
#### Results Interpretation
Accuracy: Achieved a validation accuracy of approximately 82% for gender prediction and a mean absolute error of around 18 years for age prediction.
Prediction Examples: Showcased examples of successful predictions where the model accurately identified gender and estimated age.
## Conclusion
In conclusion, the CNN model developed shows promising results in predicting age and gender from facial images. The model's ability to generalize on unseen data is demonstrated through validation metrics and prediction examples. Further improvements could involve refining the model architecture, augmenting the dataset, or exploring additional preprocessing techniques to enhance accuracy and robustness. This project highlights the potential of deep learning in facial recognition tasks and its applications in real-world scenarios like demographic analysis and personalized services.

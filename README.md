EfficientNet-CMR-HF-Diagnosis
An Intelligent Ensemble EfficientNet Prediction System for Cardiac MRI-Based Heart Failure Severity Diagnosis
Overview
This project focuses on diagnosing heart failure severity using an ensemble of EfficientNet models (B0–B7) trained on cardiac magnetic resonance (CMR) images. The system utilizes multiple EfficientNet variants optimized with Adam, SGD, and RMSprop optimizers to enhance predictive accuracy.


Key Features
Uses EfficientNet models (B0–B7) for feature extraction from CMR images.
Evaluates model performance with Adam, SGD, and RMSprop optimizers.
Selects the best-performing models based on sensitivity and specificity.
Combines predictions using a weighted ensemble method.
Achieves a testing accuracy of 0.95 with significant improvements in class-wise sensitivity.
Dataset
Source: Kaggle’s Data Science Bowl challenge ((https://www.kaggle.com/c/se
cond-annual-data-science-bowl)
Total Samples: 2141 T1-weighted short-axis view CMR cine-sequences
Subjects: 890 individuals (healthy & HF cases)
Classes: Hyperdynamic, Mild, Moderate, Normal, Severe
Metadata:
Age group: 20–60 years
Slice thickness: 6–8 mm
Pixel spacing: 0.6490–1.7969 mm/pixel


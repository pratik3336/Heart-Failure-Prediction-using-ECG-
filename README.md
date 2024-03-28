# Heart-Failure-Prediction-using-ECG-
Using Logistic Regression, Random Forest and XgBoost to predict heart failure

Models implemented:

Extra trees classifier
Gradient Boosting Classifier
Random Forest Classifier
CatBoost Classifier
Light Gradient Boosting Machine
Decision Tree Classifier
Best performing model : Ensemble of the models implemented (except Decision tree) with Soft Voting.

Final model : Calibrated version of the best model using pycaret

ECG Heartbeat Classification Algorithms:

Logistic Regression
Random Forest
XgBoost
Performed Minority Sampling using SMOTE technique as data had imbalance.

Best performing model - Random Forest (in both ases with and without SMOTE).


# Heart Analysis using ECG and Heart Failure Prediction

## Introduction

Heart diseases stand as the principal cause of mortality worldwide, claiming over a million lives annually, with a significant proportion occurring under the age of 70. The quest for preventing, alleviating, and eventually curing heart conditions is a global endeavor, driven by research and clinical practice. 

In this context, machine learning models emerge as powerful tools for enhancing diagnostic accuracy and intervention timeliness. 

Furthermore, Electrocardiography (ECG) is a cornerstone in cardiac health monitoring, utilized extensively by healthcare professionals. However, manual ECG analysis poses substantial challenges due to the complexity of interpreting varying waveforms and morphologies, a task that is both time-intensive and susceptible to human error.

This project embarks on an analytical journey to assess the risk of heart failure, leveraging diverse data analysis techniques to explore the correlation between various risk factors and heart disease. Employing machine learning models, we aim to predict the presence of heart disease in individuals. 

Additionally, this study delves into ECG signal analysis, categorizing signals into five distinct classes. Addressing the manual analysis challenges, our research incorporates three machine learning implementations for precise anomaly detection in ECG signals, contributing to the advancement of cardiac health diagnostics.

## Project Objectives

- To analyze the risk factors associated with heart diseases and observe trends that contribute to heart failure.

- To implement and evaluate machine learning models for predicting the likelihood of heart disease in individuals.

- To classify ECG signals into five categories, enhancing the accuracy and efficiency of cardiac monitoring.

## Technologies and Techniques

- **Data Analysis**: Employing statistical and data visualization techniques to explore correlations between heart disease risk factors.

- **Machine Learning Models**: Implementing various algorithms to predict heart disease presence based on clinical and physiological features.

- **ECG Signal Classification**: Utilizing machine learning to automate the categorization of ECG signals, improving diagnostic processes.

## Dataset

The dataset used in this project comprises clinical, demographic, and physiological parameters, along with ECG signal data categorized for analysis. Detailed information about the dataset sources and characteristics will be provided in the project documentation.

![image](https://github.com/pratik3336/Heart-Failure-Prediction-using-ECG-/assets/76115015/244e9139-296c-48f9-9b43-eabebb2064d8)


## License

This project is licensed under the MIT License - see the LICENSE file for details.

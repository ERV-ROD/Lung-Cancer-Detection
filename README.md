# Lung Cancer Detection with Machine Learning

This research project focuses on integrating advancements in Machine Learning to develop systems for the detection and classification of lung cancer progression in patients with various medical conditions.

## Objectives
- Develop machine learning models for early detection of lung cancer.
- Utilize pre-trained models to enhance accuracy and efficiency.
- Provide a tool for medical professionals to assess lung cancer progression.

## Methodology
To carry out the project, two different models will be used. Firstly, a multi-layer perceptron will be employed to determine if a person could have lung cancer. This model will utilize information related to symptoms or habits associated with this disease.

The second model will be used to improve accuracy in cases where individuals have been identified as potential cancer patients. This second model will classify computed tomography (CT) lung images to determine if the organ is healthy or has any abnormalities. To perform this task, the pre-trained VIT model will be utilized.

Additionally, Random Forest and Cross-Validation concepts will be implemented to enhance the reliability of both models. The Random Forest algorithm will combine multiple decision trees to generate more accurate predictions and prevent model overfitting. On the other hand, Cross-Validation will allow evaluating the performance of the models on different datasets, ensuring they are robust and generalize well to new cases.

## Importance
Lung cancer is one of the most common and deadliest forms of cancer. Early detection is crucial for effective treatment and improved patient outcomes. By leveraging machine learning techniques, this project aims to improve early detection rates and potentially save lives.


## Datasets
- 📚 Tabular dataset obtained from: [Kaggle Lung Cancer Dataset](https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer)
- 📚 Image dataset available at: [Kaggle Chest CT Scan Images Dataset](https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images)

The first dataset consists of survey data in tabular format, while the second contains labeled images of different types of cancer.

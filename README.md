# Skin Disorder Prediction Using Machine Learning

## Project Overview

This project focuses on predicting six types of dermatological disorders using machine learning techniques based on clinical and histopathological attributes.

The objective is to analyse dermatological data, identify relevant patterns and develop a predictive classification model that can support preliminary research and clinical assessment.

## Objectives

- Analyse dermatological data through Exploratory Data Analysis (EDA).
- Identify important clinical and histopathological features.
- Develop and compare multiple machine learning classification models.
- Optimise the best-performing model using hyperparameter tuning.
- Explore the potential of machine learning in dermatological classification.

## Dataset Description

- **Total observations:** 366
- **Total attributes:** 34
- **Clinical attributes:** 11
- **Histopathological attributes:** 22
- **Age attribute:** 1
- **Target classes:** 6

### Disease Classes

1. Psoriasis
2. Seborrheic Dermatitis
3. Lichen Planus
4. Pityriasis Rosea
5. Chronic Dermatitis
6. Pityriasis Rubra Pilaris

## Project Workflow

1. Data Collection and Loading
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Feature Analysis
5. Train-Test Split
6. Machine Learning Model Development
7. Model Evaluation
8. Hyperparameter Tuning
9. Feature Importance Analysis

## Machine Learning Algorithms

The following algorithms were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

## Model Performance

The tuned Random Forest classifier achieved the following results:

| Evaluation Metric | Result |
|---|---:|
| Test Accuracy | 97.30% |
| Cross-Validation Macro F1 | 0.977 |
| Correct Predictions | 72/74 |

### Best Random Forest Parameters

- `n_estimators = 200`
- `max_depth = None`
- `min_samples_split = 5`
- `min_samples_leaf = 2`

## Feature Importance

Random Forest feature importance analysis was performed to identify influential clinical and histopathological attributes.

Some of the highly ranked features included:

- Fibrosis of the papillary dermis
- Koebner phenomenon
- Perifollicular parakeratosis
- Clubbing of the rete ridges
- Follicular horn plug

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Doctor Recommendations

The model may be explored as a supportive research tool for preliminary classification of dermatological disorders. Clinical examination, patient history and appropriate investigations remain essential for diagnosis.

## Limitations

- Relatively small dataset containing 366 observations.
- Unequal distribution among disease classes.
- No independent external clinical validation.
- Model predictions should not replace professional medical diagnosis.

## Future Scope

- Expand the dataset using more diverse dermatological records.
- Explore advanced machine learning algorithms.
- Apply explainable AI techniques such as SHAP and LIME.
- Investigate image-based and multimodal classification.
- Conduct external validation with dermatology professionals.

## Conclusion

This project demonstrates the application of machine learning in dermatological classification using clinical and histopathological data. The tuned Random Forest model achieved 97.30% test accuracy, showing promising performance on the available test dataset. Further independent validation is required before clinical application.

## Author

**Haarshini**

Biotechnology | Machine Learning | Data Science

**GitHub Profile:** https://github.com/pahaarshini-max

**Project Repository:** https://github.com/pahaarshini-max/Skin-Disorder-Prediction-ML

# Loan Prediction Project - README

This project investigates a loan dataset to predict loan outcomes (e.g., default, successful repayment) using machine learning techniques.

## Project Goals
1. Develop and compare machine learning models for predicting loan outcomes.
2. Analyze the impact of different features on loan decisions.
3. Provide interpretable explanations for model predictions.

## Data
- **Source:** [Kaggle Dataset - BNPL Data V1](https://www.kaggle.com/datasets/bdoey1/bnpl-data-v1)
  
## Methodology

### Data Preprocessing:
- **Loading:** Load the dataset into a pandas DataFrame.
- **Cleaning:** Analyze missing values, identify and handle outliers, address data inconsistencies.
### Feature Engineering:
- **Feature Selection:** Choose relevant features for model training.
- **Transformation:** Normalize/scale numerical features if necessary.
- **Encoding:** Encode categorical features for model compatibility (e.g., one-hot encoding, label encoding).
- **Exploration:** Perform Exploratory Data Analysis (EDA) to understand the data distribution, identify relationships between features, and visualize key insights.
### Modeling:
- **Train-Test Split:** Divide the data into training and testing sets for model training and evaluation.
#### Decision Tree Classifier:
- Train a Decision Tree Classifier using GridSearchCV for hyperparameter tuning (e.g., max depth, min samples split).
- Evaluate model performance using metrics like accuracy, F1-score, precision, recall, and log loss.
- Analyze feature importance to understand which features influence the model's predictions most.
- Utilize SHAP (SHapley Additive exPlanations) for interpretable insights into individual feature contributions to model outputs.
#### Random Forest Classifier:
- Train a Random Forest Classifier with carefully chosen hyperparameters.
- Evaluate model performance using similar metrics as the Decision Tree Classifier.
- Compare performance between the two models.
### Evaluation:
- Analyze Confusion Matrix and ROC Curve to assess model performance in classifying loan applications.
- Consider incorporating additional metrics based on project requirements (e.g., cost-sensitive learning metrics).

## Results
- Report the accuracy and performance metrics for both Decision Tree and Random Forest Classifiers.
- Discuss the feature importance analysis and SHAP explanations from the Decision Tree.
- Compare the performance of both models and highlight the advantages/disadvantages of each approach.
- Visualize key results (e.g., confusion matrix, ROC curve, feature importance plots).

## Conclusion
- Summarize the project's findings and the effectiveness of the models in predicting loan outcomes.
- Discuss limitations of the study (e.g., data availability, model assumptions) and potential improvements.
- Outline potential applications of the results in a real-world loan approval setting.

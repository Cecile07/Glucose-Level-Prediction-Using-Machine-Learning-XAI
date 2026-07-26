# Glucose Level Prediction Using Machine Learning and Explainable AI

## Project Overview

This project develops an Artificial Intelligence (AI)-based machine learning system to predict blood glucose levels using clinical and lifestyle-related features from the Framingham Heart Study dataset.

The project demonstrates an end-to-end machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model development, prediction, and evaluation.

To improve model transparency and interpretability, Explainable AI (XAI) techniques are incorporated to understand how different features influence glucose predictions. The project applies Feature Importance, Partial Dependence Plots (PDP), SHAP (SHapley Additive exPlanations), and LIME (Local Interpretable Model-Agnostic Explanations) to provide insights into model decisions.

The objective of this project is to develop an accurate and interpretable AI-driven healthcare analytics solution capable of predicting glucose levels and identifying important factors influencing blood glucose variations.

---

## Objectives

- Develop a machine learning model for predicting blood glucose levels.
- Analyze clinical and lifestyle factors affecting glucose variations.
- Perform data preprocessing and feature engineering.
- Evaluate machine learning model performance.
- Apply Explainable AI techniques to improve model transparency.
- Understand how individual features influence predictions.

---

## Dataset

**Dataset:** Framingham Heart Study Dataset

The dataset contains clinical and lifestyle-related information, including:

- Age
- Gender
- Education
- Smoking status
- Cigarettes per day
- Blood pressure medication usage
- Hypertension history
- Diabetes status
- Cholesterol level
- Blood pressure measurements
- Body Mass Index (BMI)
- Heart rate
- Glucose level

**Target Variable:**
- Glucose Level

---

## Project Workflow

### Data Preprocessing

- Data loading and exploration
- Handling missing values
- Data cleaning
- Feature selection
- Preparing data for machine learning models

### Exploratory Data Analysis (EDA)

Performed analysis to understand:

- Feature distributions
- Relationships between variables
- Correlation patterns
- Factors influencing glucose levels

### Feature Engineering

- Selecting relevant features
- Transforming input variables
- Preparing datasets for model training and evaluation

### Machine Learning Model Development

The project includes:

- Training and testing data preparation
- Model development
- Prediction generation
- Performance evaluation

---

# Explainable AI (XAI)

To improve the interpretability of the machine learning model, Explainable AI techniques were applied.

## 1. Feature Importance

Feature Importance was used to identify the most influential features affecting glucose level predictions.

This helps understand which clinical and lifestyle factors contribute most to the model's decisions.

## 2. Partial Dependence Plots (PDP)

Partial Dependence Plots were used to analyze how individual features influence model predictions.

PDP provides insights into the relationship between important features and predicted glucose levels.

## 3. SHAP (SHapley Additive exPlanations)

SHAP was applied to explain both global and individual model predictions.

It provides:

- Overall feature contribution analysis
- Understanding of how features increase or decrease predictions
- Individual prediction explanations

## 4. LIME (Local Interpretable Model-Agnostic Explanations)

LIME was used to explain individual predictions by identifying the features that positively or negatively influence a specific model output.

This provides a human-interpretable explanation of why the model generated a particular prediction.

---

## Technologies Used

**Programming Language**

- Python

**Libraries**

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP
- LIME

**Tools**

- Jupyter Notebook
- VS Code
- GitHub

---

## Repository Structure

```
Glucose-Level-Prediction-XAI/

│── Glucose_Level_Prediction_XAI.ipynb
│── README.md
│── requirements.txt
│── LICENSE
```

---

## Key Highlights

- End-to-end AI and machine learning workflow
- Healthcare-focused predictive analytics
- Exploratory Data Analysis and feature engineering
- Machine learning-based glucose prediction
- Explainable AI integration
- Feature Importance analysis
- Partial Dependence Analysis
- SHAP model interpretation
- LIME local prediction explanation

---

## Conclusion

This project demonstrates the application of Artificial Intelligence and Explainable AI in healthcare analytics by developing a machine learning system for glucose level prediction.

By combining predictive modeling with interpretability techniques, the project provides not only glucose predictions but also insights into the factors influencing model decisions. The integration of XAI methods improves transparency, trust, and understanding of AI-driven healthcare applications.

---

## Future Improvements

Future improvements could include:

- Testing additional machine learning and deep learning algorithms
- Applying advanced hyperparameter optimization
- Incorporating larger and more diverse healthcare datasets
- Developing a real-time glucose prediction application
- Exploring advanced Explainable AI methods

---
## Author

**Mbuyi Cecile Ngoie**

AI & Machine Learning Enthusiast | Data Science | Explainable AI

GitHub: https://github.com/Cecile07  
LinkedIn: https://www.linkedin.com/in/cecile-mbuyi-ngoie

## License

This project is licensed under the MIT License.

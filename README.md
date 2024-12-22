# Introduction 

Strokes are one of the leading causes of death and long-term disability worldwide. Early detection and treatment are crucial in improving patient outcomes. This project aims to develop a machine learning model to predict the likelihood of a stroke in individuals based on various health parameters and demographics. 

# Dataset Description 

The project utilizes the Stroke Prediction Dataset from Kaggle, which includes information about patients such as age, gender, hypertension, heart disease, and lifestyle factors. 

##Features: 

- id: Unique identifier 

- gender: Gender of the patient 

- age: Age of the patient 

- hypertension: Whether the patient has hypertension 

- heart_disease: Whether the patient has heart disease 

- ever_married: Marital status 

- work_type: Type of employment 

- Residence_type: Urban or rural residence 

- avg_glucose_level: Average glucose level in blood 

- bmi: Body mass index 

- smoking_status: Smoking habits 

- stroke: Target variable (1 if the patient had a stroke, 0 otherwise) 

# Project Overview
The project involves the following key steps:

1. ## Data Preprocessing
- Handling missing values in the bmi column by imputing the median.
- Encoding categorical variables using Label Encoding.
- Feature scaling using StandardScaler.
2. ## Exploratory Data Analysis (EDA)
- Analyzing distributions and relationships between variables.
- Visualizing correlations using a heatmap.
3. ## Handling Class Imbalance
- Applying SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset.
4. ## Modeling
Training a Random Forest Classifier to predict stroke occurrence.

5. ## Evaluation
- Assessing model performance using accuracy, precision, recall, F1-score, and ROC-AUC metrics.
- Visualizing results with confusion matrix and ROC curve.

# Results and Analysis
The Random Forest Classifier achieved the following performance metrics on the test set:

- Accuracy: 95%
- Precision: 96%
- Recall: 96%
- F1-Score: 96%
- ROC-AUC Score: 0.99

## Feature Importance:

The top features influencing stroke prediction were:

1. Age
2. Average Glucose Level
3. Body Mass Index (BMI)

# Dependencies
- pandas==1.3.5
- numpy==1.21.4
- scikit-learn==0.24.2
- imbalanced-learn==0.8.1
- matplotlib==3.5.0
- seaborn==0.11.2
- jupyter==1.0.0

# Visualization and Plots
## Correlation Heatmap
![image](https://github.com/user-attachments/assets/58a0de45-03f1-41c8-b277-0d82655e49ad)
## Confusion Matrix
![image](https://github.com/user-attachments/assets/eb4b541b-6c89-4c96-b526-0bff1b8817df)
## ROC Curve
![image](https://github.com/user-attachments/assets/8f7ae0cd-3168-44f0-a829-d57578ffbad6)

# Acknowledgements
- Kaggle: For providing the Stroke Prediction Dataset.
- scikit-learn Documentation: For comprehensive guides on machine learning algorithms.
- Community Contributors: For open-source libraries and tools that made this project possible.

# Contact Information
Moatasem Essameldin

- Email: motasemessam@gmail.com
- LinkedIn: linkedin.com/in/moatasem-essam-736268314
- GitHub: MoatasemEssam

# Ovarian Cancer Subtype Classification Using Gene Expression Data

This project focuses on classifying subtypes of ovarian cancer—serous, endometrioid, mucinous, and clear cell—using high-dimensional gene expression data. Given the complexity and rarity of ovarian cancer, the project aims to enhance early diagnosis and detection by leveraging machine learning techniques to identify biomarkers and classify subtypes with improved accuracy.

# Key Objectives
Categorize Ovarian Cancer Subtypes: Develop a reliable classification system for ovarian cancer subtypes to assist in early detection.
Address Class Imbalance: Employ oversampling techniques to mitigate skewed class distributions and ensure balanced model training.
Dimensionality Reduction: Handle high-dimensional gene expression data effectively to improve computational efficiency and model performance.
Model Comparison: Train multiple machine learning models and compare their performance using accuracy, precision, recall, and F1-score.

# Data Preprocessing Steps
Data Exploration: Analyzed the high-dimensional gene expression dataset to understand its structure, identify missing values, and inspect class distribution.
Normalization and Scaling: Applied normalization to standardize feature scales for consistent input to machine learning models.
Dimensionality Reduction: Implemented Principal Component Analysis (PCA) to reduce the number of features while preserving key patterns in the data.
Oversampling: Used techniques like SMOTE (Synthetic Minority Oversampling Technique) to address class imbalance in the training data.
Feature Selection: Identified the most significant genes contributing to ovarian cancer subtypes for model input.

# Machine Learning Models
This project leveraged a variety of machine learning models to classify ovarian cancer subtypes, including K-Nearest Neighbors (KNN), XGBoost, Logistic Regression, Random Forest, and Decision Trees.  KNN was optimized by tuning hyperparameters such as the number of neighbors, distance metrics, and weights using GridSearchCV. XGBoost was fine-tuned for learning rate, number of estimators, and tree depth, employing a softmax objective function to address the multiclass classification problem.

# Results
Accuracy Achieved: 78% on the test dataset, showcasing the model's reliability in classifying ovarian cancer subtypes.
Evaluation Metrics: Precision, recall, and F1-score were used to compare the effectiveness of trained models.
Model Insights: The results highlight the potential of gene expression data in subtype classification, contributing to the early diagnosis of ovarian cancer.

# Conclusion
This project demonstrates the capability of machine learning techniques to process and analyze high-dimensional biological data effectively. By classifying ovarian cancer subtypes with significant accuracy, the study contributes to improving diagnostic reliability and uncovering biomarkers for future research.

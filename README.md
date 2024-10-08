﻿# MachineLearning

 # Project Goal
The primary objective of this project is to simulate the Premier League season by predicting individual match outcomes using a combination of machine learning models. The match predictions are then aggregated to forecast the final standings of the top 6 teams. This methodology allows for a detailed analysis of match-by-match dynamics rather than relying on aggregated seasonal predictions.

 # Dataset Summary
The dataset used comprises 11,683 rows and 39 columns, covering Premier League matches over 31 years. It includes various features like goals scored, shots, corners, fouls, and betting odds, among others. The dataset was refined to focus on more recent seasons to balance historical relevance with the need for a large training sample. Feature engineering was employed to create new metrics, such as shot accuracy and defensive strength, enhancing the model's predictive capability.

# Algorithm Selection
Three machine learning algorithms were selected for this project:

Logistic Regression: Chosen for its effectiveness in handling categorical outcomes (win, draw, loss), providing a baseline for evaluating feature importance.
Random Forest: Selected for its robustness in handling both numerical and categorical data and its ability to capture non-linear interactions within the data.
Support Vector Machines (SVM): Used for its proficiency in modeling non-linear relationships, crucial for analyzing detailed match statistics.
Each model's hyperparameters were carefully configured and optimized using techniques like GridSearchCV to enhance performance.

# Challenges and Solutions
The project faced several challenges, including data discrepancies, the evolution of data availability, and the limited number of features. Solutions included standardizing data formats, expanding the training dataset to cover 10 seasons, and using feature engineering to create additional relevant features. Despite these efforts, the model's accuracy could be further improved by incorporating more domain-specific features and advanced preprocessing techniques.

# Evaluation and Results
The models were evaluated using metrics like accuracy, precision, recall, and F1-score. The Random Forest model emerged as the most accurate, especially after hyperparameter tuning, achieving an accuracy of 63.18%. The project highlighted the importance of continuous model refinement, with the Random Forest model demonstrating the best balance between accuracy and the ability to predict different match outcomes.

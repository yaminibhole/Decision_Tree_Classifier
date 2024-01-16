# DECISION TREE CLASSIFIER
This repository contains code and insights from a project focused on building a predictive model for term deposit subscriptions in a banking context. The goal is to assist a Portuguese banking institution in tailoring its marketing efforts effectively.
# Dataset
The dataset used for this project is sourced from the UCI Machine Learning Repository and is related to direct marketing campaigns of a Portuguese banking institution. It includes demographic and behavioral data, such as age, occupation, education level, and more.

Key Insights
# Data Pre-processing:
The dataset was well-structured with no missing values.
Duplicate entries were observed but were deemed intentional, representing different campaigns targeting the same clients.

# Exploratory Data Analysis (EDA):
1. Majority of clients fell in the 30-40 age range, coinciding with the highest subscription rate for term deposits.
2. Certain occupations (administrative, blue-collar, technician) had higher subscription rates.
3. Marital status leaned heavily toward the "married" category.
4. Clients with higher education levels had a higher subscription rate.
5. Housing loans correlated positively with term deposit subscriptions, while personal loans showed a negative correlation.

# Model Building and Evaluation:
1. Implemented a Decision Tree classifier with an accuracy rate of approximately 91.52% on training and testing data.
2. Cross-validation confirmed the robustness of the model, achieving an accuracy score of around 91.60%.
3. The classification report revealed a balanced model with reasonable precision, recall, and F1-scores.

# Future Directions:
1. Explore other machine learning algorithms or ensemble methods to enhance predictive accuracy.
2. Address multicollinearity among input features through feature engineering and selection methods.
3. Consider incorporating external data sources for additional insights.
4. Explore real-time deployment of the model into operational systems for automated decision-making.

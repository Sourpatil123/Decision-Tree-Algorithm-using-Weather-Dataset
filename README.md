# Decision-Tree-Algorithm-using-Weather-Dataset

🌦️ Decision Tree Algorithm using Weather Dataset
📘 Overview

This project demonstrates how to implement a Decision Tree Classifier to predict whether a person will play or not based on different weather conditions.
It uses a small weather dataset with categorical and boolean features such as Outlook, Temperature, Humidity, and Windy to predict the target variable Play.

🧠 Objective

The main goal of this project is to understand how the Decision Tree algorithm works and how it can be used for classification tasks in Machine Learning.

| Outlook  | Temperature | Humidity | Windy | Play |
| -------- | ----------- | -------- | ----- | ---- |
| Sunny    | Hot         | High     | False | No   |
| Sunny    | Hot         | High     | True  | No   |
| Overcast | Hot         | High     | False | Yes  |
| Rain     | Mild        | High     | False | Yes  |
| Rain     | Cool        | Normal   | False | Yes  |
| Rain     | Cool        | Normal   | True  | No   |
| Overcast | Cool        | Normal   | True  | Yes  |
| Sunny    | Mild        | High     | False | No   |
| Sunny    | Cool        | Normal   | False | Yes  |
| Rain     | Mild        | Normal   | False | Yes  |
| Sunny    | Mild        | Normal   | True  | Yes  |
| Overcast | Mild        | High     | True  | Yes  |
| Overcast | Hot         | Normal   | False | Yes  |
| Rain     | Mild        | High     | True  | No   |

⚙️ Features Used

Outlook → (Sunny, Overcast, Rain)

Temperature → (Hot, Mild, Cool)

Humidity → (High, Normal)

Windy → (True, False)

Play (Target Variable) → (Yes, No)

🧩 Steps Performed

Data Collection — Created a simple weather dataset.

Data Preprocessing — Converted categorical data into numeric using LabelEncoder.

Model Training — Trained a DecisionTreeClassifier from sklearn.tree.

Prediction — Tested the model with different weather inputs.

Visualization — Visualized the decision tree structure using plot_tree.

📊 Evaluation

Algorithm: Decision Tree Classifier

Criterion: Entropy (Information Gain)

Training Accuracy: ~100% (on small dataset, may overfit)

Use Case: Categorical Classification

🧠 Key Learnings

Decision Tree splits data using information gain or Gini index.

Helps in understanding decision-making flow visually.

Easy to interpret but prone to overfitting on small datasets.

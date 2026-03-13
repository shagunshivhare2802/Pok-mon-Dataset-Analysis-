📊 Pokémon Dataset Analysis & Legendary Classification
📌 Project Overview

This project presents an end-to-end data analytics and machine learning workflow using a Kaggle-style Pokémon dataset. The goal is to uncover patterns in Pokémon characteristics—such as types, combat stats, generations, and Legendary status—through exploratory data analysis (EDA), feature engineering, and predictive modeling.

The project emphasizes real-world analytical practices, including handling class imbalance and evaluating models with appropriate metrics beyond accuracy.

📂 Dataset

Size: 180 Pokémon

Format: Kaggle-style CSV

Key Features:

Pokémon types (Type 1, Type 2)

Combat stats (HP, Attack, Defense, Sp. Atk, Sp. Def, Speed, Total)

Pokédex attributes (Height, Weight, Base Experience, Capture Rate)

Generation information

Target variable: Legendary status

🔍 Exploratory Data Analysis (EDA)

The EDA focuses on:

Distribution of Pokémon types and generations

Comparison of Legendary vs non-Legendary Pokémon

Stat distributions and correlations

Analysis of Pokédex attributes such as capture rate, height, and weight

Key insights from EDA guide downstream feature engineering and modeling decisions.

🛠 Feature Engineering

Custom features were created to capture deeper patterns:

Attack-to-Defense Ratio – offensive vs defensive bias

Speed-to-Total Ratio – agility-focused Pokémon

Dual-Type Indicator – structural advantage of having two types

One-hot encoding of Pokémon types for machine learning models

🤖 Machine Learning

Model: Random Forest Classifier

Problem: Binary classification (Legendary vs non-Legendary)

Challenges Addressed:

Class imbalance handled using class weights

Categorical variables encoded properly

📈 Model Evaluation

Instead of relying on accuracy, the project uses:

ROC–AUC for overall class separation

Precision–Recall Curve to evaluate minority (Legendary) class performance

These metrics provide a more realistic evaluation for imbalanced datasets.

✅ Key Takeaways

Legendary Pokémon are statistically stronger but not trivially separable

Pokémon types and engineered ratios significantly improve prediction quality

Proper evaluation metrics are critical when working with imbalanced data

EDA-driven feature engineering leads to more interpretable models


Add XGBoost or LightGBM with hyperparameter tuning

Apply SHAP for model explain

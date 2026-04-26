# 🚢 Titanic Survival Prediction (Advanced ML)

This repository contains a high-precision Machine Learning model developed to predict passenger survival on the Titanic using the **Random Forest** algorithm and **Advanced Feature Engineering**.

## 🚀 Project Overview
The goal was to move beyond basic classification and implement domain-specific logic to achieve a competitive ranking on Kaggle.

## 🛠️ Key Hacker Logic Implemented
* **Title Extraction:** Extracted titles (Mr, Miss, Master, Rare) from names to capture social status and the "Women and Children First" maritime protocol.
* **Smarter Imputation:** Filled missing Age values based on the median age of specific Title groups rather than a global average.
* **Family Dynamics:** Created a `FamilySize` feature to account for the fact that families often survived or perished together.
* **Fare Binning:** Categorized fares into bins to reduce the noise from outliers and improve model generalization.

## 📊 Technical Stack
* **Language:** Python 3
* **Libraries:** Pandas, NumPy, Scikit-Learn
* **Model:** Random Forest Classifier (Optimized with 500 estimators)

## 🏆 Achievement
* **Kaggle Competitive Score:** Top Tier Rank
* **Portfolio Status:** Active Research Project

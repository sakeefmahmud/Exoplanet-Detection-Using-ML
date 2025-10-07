# 🌌 Exoplanet Detection Using Machine Learning

This project focuses on predicting the presence of exoplanets using a dataset containing stellar, orbital, and photometric features. By applying machine learning techniques, the goal is to identify which signals correspond to confirmed exoplanets and to provide a reliable prediction framework.

---

## 🔍 Project Overview

Exoplanet detection is a critical task in astronomy, requiring analysis of large datasets containing stellar and orbital characteristics. This project leverages features such as magnitudes (`j_mag`, `h_mag`, `k_mag`, `kep_mag`), stellar parameters (`star_teff`, `star_logg`, `star_mass`, `star_radius`), orbital parameters (`planet_radius`, `orbital_period`), and PCA components (`PC1`, `PC2`, `PC3`) to train supervised machine learning models for exoplanet classification.

Key objectives include:

* Building predictive models to classify exoplanet candidates
* Handling class imbalance in the dataset
* Performing feature engineering and scaling
* Evaluating multiple models for accuracy and robustness

---

## ⚙️ Methodology

### 1. **Data Preprocessing**

* Handled missing values and inconsistencies
* Applied feature scaling and normalization
* Addressed class imbalance using SMOTE or class weighting

### 2. **Feature Engineering**

* Derived new features from magnitudes and orbital parameters
* Log transformations for skewed variables
* Feature selection based on model importance

### 3. **Model Training & Comparison**

Multiple machine learning models were trained and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting
* AdaBoost
* Support Vector Machine (SVM)
* Naive Bayes
* K-Nearest Neighbors (KNN)

Evaluation metrics include **F1-score, precision, recall, ROC-AUC**, and accuracy, with emphasis on metrics that handle imbalanced datasets.

### 4. **Feature Importance Analysis**

Tree-based models were used to identify the most influential features affecting exoplanet detection, providing insights for both model interpretation and astrophysical understanding.

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn, Imbalanced-learn
* **Tools:** Jupyter Notebook / Google Colab


---



## 🚀 Key Outcomes

* Built and validated multiple machine learning models for exoplanet detection
* Addressed data imbalance for reliable predictions
* Identified key features influencing exoplanet detection
* Provided a workflow that can be extended to larger astronomical datasets

---

## 📚 Acknowledgments

* Dataset sourced from **Kaggle**
* Inspired by machine learning applications in astrophysics and astronomy research


Do you want me to do that?

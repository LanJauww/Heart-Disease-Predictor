# Heart-Disease-Predictor
  This project successfully developed a heart disease prediction system using supervised machine learning models applied to structured clinical data. The system leverages commonly used classifiers such as K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Artificial Neural Network (ANN), providing an efficient mechanism to predict whether a patient is likely to have heart disease based on key attributes like age, blood pressure, cholesterol, heart rate, and ECG results. Users can input patient details through a graphical user interface (GUI), where the models analyze the inputs and return both the prediction and the associated probability of heart disease presence.

  The core objective of this system is threefold. First, it enables real-time prediction by processing new patient data and providing immediate risk classification. This helps medical professionals and users evaluate health risks early. Second, it includes comprehensive evaluation of each model using metrics like accuracy, precision, recall, F1 score, and classification reports. Enhanced versions of the models, utilizing PCA for dimensionality reduction and GridSearchCV
for hyperparameter tuning, further improve performance and interpretability. Third, the inclusion of multiple models empowers users to compare outcomes and select the best-performing one based on empirical evidence.

  By visualizing confusion matrices and allowing direct model comparisons within the GUI, the system not only meets technical goals but also prioritizes usability. Ultimately, it aids in proactive healthcare decisions by making predictions transparent, reproducible, and accessible through a well-integrated and explainable machine learning pipeline.

Limitations:
- The dataset lacks lifestyle or genetic features (e.g. smoking habits, family history, diet, activity level) that are known to influence heart disease risk.
- Categorical features are encoded simplistically (e.g., no ordinal encoding where appropriate).
- The model is trained and tested on a fixed dataset without considering externalvalidation or real-world, unseen data.
- There's no cross-dataset generalization test, so we can't guarantee robustness across populations.

Kaggle dataset selected:
https://www.kaggle.com/datasets/rishidamarla/heart-disease-prediction/data


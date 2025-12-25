## **California Housing Price Prediction using Machine Learning**

### **Project Description**

Developed an end-to-end machine learning pipeline to predict **California housing prices** using multiple regression algorithms. The project focused on building a **scalable, efficient, and production-ready workflow** from data preprocessing to model deployment.

### **Key Highlights**

* Performed **data loading and preprocessing** on `housing.csv`, handling missing values, feature scaling, and categorical encoding using a **custom preprocessing pipeline**.
* Applied **stratified train-test splitting** based on income categories to preserve data distribution across datasets.
* Trained and evaluated multiple regression models:

  * Linear Regression
  * Decision Tree Regressor
  * Random Forest Regressor
* Used **cross-validation** to compare model performance and minimize overfitting.
* Identified **Random Forest Regressor** as the best-performing model, achieving the **lowest RMSE** and most consistent results.

### **Production-Ready Implementation**

* Implemented a Python script that:

  * Trains the Random Forest model and saves it using **joblib**.
  * Uses conditional logic to **skip retraining** if a trained model already exists.
  * Loads new input data (`input.csv`) and generates predictions for `median_house_value`.
  * Saves predictions to `output.csv` for downstream use.
* Designed the pipeline for **efficiency, reproducibility, and deployment readiness**.

### **Technologies Used**

`Python`, `Scikit-learn`, `Pandas`, `NumPy`, `Joblib`, `Machine Learning Pipelines`

# House-prices-prediction-using-Machine-learning

# Regression Analysis Project

## 📌 Overview

This project demonstrates an end-to-end machine learning workflow for solving a regression problem. It includes:

* Exploratory Data Analysis (EDA)
* Feature Engineering (FE)
* Feature Selection (FS)
* Feature Scaling (Min-Max Scaling)
* Model Training and Evaluation (Regression Models)

The project is organized into three main Jupyter notebooks that guide the workflow from raw data exploration to predictive modeling.

---

## 📂 Project Structure

```
.
├── 01_EDA.ipynb
├── 02_EDA_FE_FSScaling_min_max_RandomFR.ipynb
├── 03_Regression.ipynb
└── README.md
```

### 1️⃣ 01_EDA.ipynb

* Initial data exploration
* Understanding dataset structure
* Handling missing values
* Data visualization
* Identifying correlations and patterns

### 2️⃣ 02_EDA_FE_FSScaling_min_max_RandomFR.ipynb

* Advanced EDA
* Feature Engineering
* Feature Selection
* Min-Max Scaling
* Random Forest-based feature importance

### 3️⃣ 03_Regression.ipynb

* Model building for regression
* Training and testing split
* Model evaluation using regression metrics
* Performance comparison

---

## ⚙️ Technologies Used

* Python 3.x
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🚀 Workflow Summary

1. Data Loading
2. Exploratory Data Analysis
3. Data Cleaning
4. Feature Engineering
5. Feature Scaling
6. Feature Selection
7. Model Training
8. Model Evaluation
9. Performance Optimization

---

## 📊 Model Evaluation Metrics

Common regression metrics used:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 🛠 How to Run the Project

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Run notebooks in order:

   * Start with `01_EDA.ipynb`
   * Then `02_EDA_FE_FSScaling_min_max_RandomFR.ipynb`
   * Finally `03_Regression.ipynb`

---

## 📌 Key Highlights

* Structured ML workflow
* Clear separation of preprocessing and modeling
* Feature importance analysis
* Scalable and reproducible approach

---

## 📎 Future Improvements

* Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
* Cross-validation improvements
* Model deployment (Flask / FastAPI)
* Experiment tracking (MLflow)

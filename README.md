# Titanic Survival Prediction

![Python](https://img.shields.io/badge/Python-3.11-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.3-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green.svg)
![Kaggle](https://img.shields.io/badge/Kaggle-0.74880-success.svg)


### Overview  
This project uses data analysis and machine learning to predict passenger survival on the Titanic 
Implemented a pipeline that includes **EDA, feature engineering, model comparison, hyperparameter tuning, and feature importance analysis**.  
Final model achieved a kaggle score of 0.74880.  

<img width="1444" height="170" alt="image" src="https://github.com/user-attachments/assets/85bae989-6585-4478-a811-4b6d200df744" />


---

### Approach  
1. **Exploratory Data Analysis (EDA)** – survival by sex, passenger class, age, fare, embarkation port.  
2. **Feature Engineering** – extracted titles, created family size, handled missing values, encoded categoricals.  
3. **Modeling** – compared Logistic Regression, Random Forest, Gradient Boosting with cross-validation.  
4. **Hyperparameter Tuning** – optimized Random Forest with grid search.  
5. **Feature Importance** – identified top predictors: **Sex, Pclass, Fare, Title, Age**.  

---

### Summary of different features on a correlation heatmap:
<img width="700" height="500" alt="image" src="https://github.com/user-attachments/assets/b0b28a10-a21e-42d4-a042-d1f1b2c29682" />

### Summary of most imporant features for predictions:
<img width="700" height="500" alt="image" src="https://github.com/user-attachments/assets/e8e0f2c7-83af-4e8c-9022-3203ea717f76" />


---

### Results  
- **Best Model:** Gradient Boosting Classifier  
- **Kaggle Score:** **0.74880**  
- **Key Features:** Sex, Pclass, Fare, Title, Age  

---

## How to Run

Clone the repository and open the Jupyter notebook:

```bash
git clone https://github.com/KasimM05/Titanic_predictions.git
cd Titanic_predictions
jupyter notebook Titanic.ipynb

```

## Requirements

Install dependencies with:

```bash
pip install -r requirements.txt

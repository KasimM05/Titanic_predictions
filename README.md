# Titanic Survival Prediction

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

### Results  
- **Best Model:** Gradient Boosting Classifier  
- **Kaggle Score:** **0.74880**  
- **Key Features:** Sex, Pclass, Fare, Title, Age  

---

### How to Run  
```bash
git clone https://github.com/KasimM05/Titanic_predictions.git
cd Titanic_predictions
jupyter notebook Titanic.ipynb

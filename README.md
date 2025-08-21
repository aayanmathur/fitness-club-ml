# fitness-club-ml

## Overview  
This project builds a machine learning pipeline to **predict whether a member will attend a booked fitness class**.  
Fitness clubs often face the challenge of full bookings with low actual attendance.  
By anticipating no-shows, clubs can **free up spots, improve utilization, and enhance member experience**.  

The notebook walks through the **entire ML workflow**, from data preparation to model evaluation and interpretation.

---

## Workflow  

1. **Data Preparation**  
   - Handle missing values and clean raw features  
   - Encode categorical variables  

2. **Feature Engineering**  
   - Booking urgency (last-minute vs planned)  
   - Weekend/weekday classes  
   - Morning/evening slots  
   - Member tenure groups  

3. **Exploratory Data Analysis (EDA)**  
   - Attendance patterns across categories, time, booking behavior  
   - Correlation analysis to identify impactful features  

4. **Modeling**  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - Gradient Boosting  

5. **Evaluation**  
   - Cross-validation with ROC-AUC  
   - Confusion matrices & classification reports  
   - ROC curves comparison  

6. **Feature Importance**  
   - Tree-based feature importances  
   - Logistic Regression coefficients  

---

## Tech Stack  
- **Python**: pandas, numpy, matplotlib, seaborn  
- **Scikit-learn**: preprocessing, modeling, evaluation  

---

## Future Work
Hyperparameter tuning for optimized performance
Experiment with additional algorithms (XGBoost, LightGBM)
Deploy best model as an API for real-time predictions

---




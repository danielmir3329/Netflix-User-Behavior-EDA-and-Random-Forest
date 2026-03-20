# Netflix User Behavior Analysis and Churn Prediction

## Project Overview
This project analyzes user behavior data from a streaming platform to understand engagement patterns and predict customer churn using a Random Forest classification model. The objective is to identify key behavioral indicators associated with churn and provide actionable insights to improve customer retention.

---

## Objectives
- Analyze user engagement and behavioral patterns  
- Identify key factors influencing customer churn  
- Develop a predictive model using Random Forest  
- Evaluate model performance using standard classification metrics  
- Generate data-driven business recommendations  

---

## Dataset Description
The dataset contains user-level behavioral and engagement metrics.

### Features
- `avg_watch_time_minutes`: Average viewing time per session  
- `watch_sessions_per_week`: Number of sessions per week  
- `completion_rate`: Percentage of content completed  
- `binge_watch_sessions`: Number of binge-watching sessions  
- `recommendation_click_rate`: Interaction rate with recommendations  
- `rating_given`: User rating behavior  
- `subscription_length`: Duration of user subscription  

### Target Variable
- `churned`: Indicates whether a user has churned (Yes/No)

---

## Methodology

### Data Preprocessing
- Checked and handled missing values  
- Converted categorical variables to appropriate formats  
- Performed feature scaling where necessary  
- Split data into training and testing sets  

### Exploratory Data Analysis
- Analyzed distributions of key variables  
- Compared behavioral patterns between churned and retained users  
- Examined correlations among features  

### Model Development
- Implemented a Random Forest classifier  
- Trained the model on behavioral features  
- Performed basic hyperparameter tuning  

### Model Evaluation
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

---

## Key Insights
- Lower engagement (watch time and session frequency) is strongly associated with churn  
- Users with low recommendation interaction are more likely to leave  
- Shorter subscription duration increases churn likelihood  
- Higher completion rates are associated with retained users  

---

## Business Recommendations
- Enhance recommendation algorithms to improve engagement  
- Target low-activity users with personalized content strategies  
- Provide incentives for users with shorter subscription durations  
- Promote high-retention content categories to encourage continued usage  

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  


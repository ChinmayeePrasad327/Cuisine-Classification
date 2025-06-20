# 🍽️ Cuisine Classification using Machine Learning

A machine learning project to classify restaurants based on their cuisines using the Random Forest Classifier. This project was done as part of a task from **Cognifyz Technologies**.

## 🔍 Problem Statement

The objective is to develop a classification model that predicts the cuisine type of a restaurant given various features like location, type, and more.

## 📁 Dataset Structure[https://www.kaggle.com/competitions/cuisine-classification-challenge/data]

- `train_features.csv`: Restaurant features (e.g., location, restaurant type, etc.)
- `train_labels.csv`: Corresponding cuisine labels
- `test_features.csv`: Features for prediction

## ⚙️ Technologies Used

- Python 🐍
- Pandas & NumPy
- Scikit-learn
- Random Forest Classifier
- Label Encoding & One-Hot Encoding
- RandomizedSearchCV for hyperparameter tuning

## 🧪 Model Evaluation

- Accuracy
- Precision, Recall, F1-score
- Classification report
- Cross-validation (RandomizedSearchCV)

### 📊 Model Performance Comparison

| Metric           | Before Tuning 🎯 | After Tuning 🔧 |
|------------------|------------------|-----------------|
| Accuracy         | 0.86             | 0.98            |
| Precision (macro)| 0.86             | 0.97            |
| Recall (macro)   | 0.74             | 0.99            |
| F1-Score (macro) | 0.75             | 0.99            |

> ✅ The fine-tuned model clearly improved performance across all key metrics using `RandomizedSearchCV`.


## 🧠 Key Learnings

- Data preprocessing and handling missing values
- Merging and encoding categorical features
- Model training and hyperparameter optimization
- Interpreting model performance using classification metrics

## 📈 Future Enhancements

- Try XGBoost or LightGBM for improved performance
- Deploy as a Streamlit web app for real-time predictions
- Add more feature engineering for better accuracy


---

## 🙋‍♀️ About Me  
Hey there! I’m **P.V.R.B. Chinmayee**—a B.Tech CSE (AI & ML) student from Vijayawada, passionately exploring the intersection of **machine learning and innovation**.

📎 Let’s connect: [LinkedIn](https://www.linkedin.com/in/chinmayee-prasad-6b788a282/)  

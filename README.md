# 🎥 YouTube Video View Predictor

This machine learning project predicts the number of views a YouTube video might receive based on its metadata using **Linear Regression**.

## 🚀 Project Overview

- **Input:** Video metadata (title, description, tags, like count, comment count, publish time)
- **Output:** Predicted number of views
- **Model:** `LinearRegression` from `scikit-learn`
- **Evaluation:** MSE, RMSE, MAE, R² Score

## 📁 Files Included

| File                  | Description                                  |
|-----------------------|----------------------------------------------|
| `youtube_data.csv`    | Input dataset (must be pre-cleaned)          |
| `linear_model.pkl`    | Trained regression model                     |
| `model_features.pkl`  | List of features used in training            |
| `model_training.py` or `.ipynb` | Main script or notebook with training code |
| `README.md`           | Project documentation                        |

## 📊 Features Used

- Title length
- Description length
- Number of tags
- Like count
- Comment count
- Hour of publication
- Day of the week of publication

## 🧪 Evaluation Metrics

| Metric               | Description                      |
|----------------------|----------------------------------|
| MSE                  | Mean Squared Error               |
| RMSE                 | Root Mean Squared Error          |
| MAE                  | Mean Absolute Error              |
| R² Score             | Coefficient of Determination     |


📝 Model Evaluation Output Example

Evaluation:
 - MSE: 845691801.24
   
 - RMSE: 29079.89
   
 - MAE: 17341.67
   
 - R²: 0.741
   
🔐 Notes:

Ensure the dataset has columns: title, description, tags, like_count, comment_count, published_at, view_count.


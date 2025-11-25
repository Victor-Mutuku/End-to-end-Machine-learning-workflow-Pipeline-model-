# California Housing KNN Regression

## Objective
Predict California housing prices using a K-Nearest Neighbors (KNN) regression model, demonstrating an end-to-end classical machine learning workflow.

## Skills Demonstrated / Concepts Applied
- **Predictive Modeling & Classical ML:** Built KNN regression model using scikit-learn.
- **Data Preprocessing:** Handled missing values with `SimpleImputer` and scaled numerical features with `StandardScaler`.
- **Feature Engineering:** Selected numerical features and combined preprocessing steps using `ColumnTransformer`.
- **Pipeline Creation:** Integrated preprocessing and model into a scikit-learn `Pipeline` for reproducibility.
- **Hyperparameter Tuning:** Optimized `n_neighbors`, `weights`, and `p` using `GridSearchCV`.
- **Model Evaluation:** Measured performance using R², Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
- **Model Persistence:** Saved trained pipeline with `pickle` for future use.

## Outputs / Visualizations
- Preprocessing pipeline summary and hyperparameter tuning results
- Model evaluation metrics: R², MSE, RMSE
- Predictions on the test dataset


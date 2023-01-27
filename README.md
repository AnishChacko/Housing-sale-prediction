## Housing-sale-prediction
# XGBoost model optimization using GridSearch method,
# Reading Housing Data
# Data Preprocessing
# Exploratory data analysis
# Feature Scaling
# XGBoost modelling (Xtreme Gradient Boosting) finding the best set of hyperparameters and tuning
                        random_state=42,
                        max_depth=8,
                        learning_rate = 0.1,
                        n_estimators = 1000,
                        colsample_bylevel = 0.4,
                        reg_alpha = 0.5,
                        subsample = 0.8,
# Model Optimization-GridSearchCV method for searching for the best hyperparameters for a given model by specifying a range of values for each hyperparameter and training the model multiple times with different combinations of hyperparameters

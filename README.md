# Task-16-Hyperparameter-Tuning-using-GridSearchCV

## Objective
To optimize a RandomForest model using GridSearchCV on the Breast Cancer dataset.
## Steps Performed
1. Loaded Breast Cancer dataset from sklearn
2. Split data into training and testing sets
3. Trained default RandomForest model
4. Applied GridSearchCV with parameter grid
5. Found best hyperparameters
6. Compared default vs tuned model performance
## Best Parameters
- n_estimators: 200
- max_depth: None
- min_samples_split: 2
## Results
| Model | Accuracy |
|-------|----------|
| Default RandomForest | 0.9649 |
| Tuned RandomForest | 0.9649 |
## Conclusion
Hyperparameter tuning confirmed that the default RandomForest configuration was already optimal for this dataset. GridSearchCV helped validate the best parameter combination and ensured reliable performance.

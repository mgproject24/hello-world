Conclusion

In this project, a complete end-to-end machine learning pipeline was developed to predict California housing prices using structured tabular data. The workflow began with robust data preprocessing, including handling missing values, feature scaling, and categorical encoding through a custom preprocessing pipeline to ensure consistency and reproducibility.

To maintain representative data distribution, stratified sampling based on income categories was applied during train–test splitting. Multiple regression models—Linear Regression, Decision Tree Regressor, and Random Forest Regressor—were trained and evaluated using cross-validation. Among these, the Random Forest Regressor demonstrated superior performance, achieving the lowest RMSE and providing more stable predictions across validation folds.

The final pipeline includes a production-oriented script that conditionally retrains the model only when required, persists the trained model using joblib, and generates predictions on new, unseen data. Predictions are automatically stored in an output file, making the system efficient, reusable, and deployment-ready.

Overall, this project demonstrates practical experience in data preprocessing, model evaluation, experiment comparison, and production-ready ML workflows.

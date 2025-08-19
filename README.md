# Forest-Cover-Type-Classification
Predict forest cover type using UCI Covertype data. Clean and scale features, train multi-class models (RF, XGBoost, LR, etc.), evaluate with accuracy, confusion matrices, and feature importance. Bonus: compare models and tune hyperparameters.


This task focuses on predicting the type of forest cover using the Covertype (UCI) dataset, which contains cartographic and environmental attributes such as elevation, slope, aspect, soil type, and distance to hydrology.

The workflow begins with data preprocessing, where missing values are handled and categorical features are properly treated. Continuous features like elevation, slope, and distances are scaled for uniformity, while binary features (e.g., soil type indicators, wilderness areas) are preserved as-is.

Next, the dataset is split into training and testing sets, ensuring stratification for balanced class representation. Several multi-class classifiers are then trained, including Random Forest, Logistic Regression, Decision Tree, SVM, K-Nearest Neighbors, Naive Bayes, and XGBoost. Predictions are evaluated using accuracy scores, classification reports, and confusion matrices to capture per-class performance.

The project also includes visualization of confusion matrices to assess model misclassifications and feature importance plots (from Random Forest) to highlight the most influential environmental factors.

As an advanced step, hyperparameter tuning with GridSearchCV is performed for both Random Forest and XGBoost, ensuring optimized performance. Finally, results from multiple models are compared side by side, demonstrating trade-offs in accuracy and interpretability.

This task provides experience in multi-class classification, tree-based modeling, and practical model evaluation and tuning for real-world ecological prediction problems.

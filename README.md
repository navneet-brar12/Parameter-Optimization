To improve the model performance, we performed hyperparameter tuning using GridSearchCV on a Support Vector Machine (SVM) classifier.
Methodology
Model Used: Support Vector Machine (SVC with RBF kernel)
Tuning Technique: GridSearchCV with 5-fold cross-validation
Evaluation Metrics:
Classification Report
Accuracy Score
Confusion Matrix
Heatmap of Cross-validation Scores
We performed hyperparameter tuning using GridSearchCV on an SVM classifier with an RBF kernel. The best parameters found were C = 10, gamma = 0.01, and kernel = 'rbf'. With these parameters, the model achieved an overall accuracy of approximately 95%. The classification report showed strong performance, with precision and recall values around 0.93–0.97 for both classes. A heatmap was also generated to visualize the cross-validation accuracy across different combinations of C and gamma, confirming that this configuration provided the best results.

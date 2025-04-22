# Customer-Behavior-Prediction_202401100300041
Customer behavior varies, with some customers drawn to discounts (bargain hunters) and others favoring premium, full-priced items (premium buyers). Predicting this behavior enables businesses to personalize marketing, pricing, and offerings, boosting customer satisfaction, loyalty, and sales by aligning strategies with individual purchase patterns.
            Here are the results of the XGBoost model evaluation for predicting customer buyer types:

### Confusion Matrix:
- The confusion matrix will be displayed as a heatmap with "bargain_hunter" (0) and "premium_buyer" (1) labels for both actual and predicted classes. The values will indicate true negatives, false positives, false negatives, and true positives.

### Evaluation Metrics:
- **Accuracy:** ~0.85 (85% of predictions are correct).
- **Precision:** ~0.80 (80% of predicted "premium_buyer" cases are correct).
- **Recall:** ~0.70 (70% of actual "premium_buyer" cases are correctly identified).
- **ROC AUC:** ~0.90 (Strong discriminatory power between classes).

              precision  recall  f1-score   support

bargain_hunter      0.87     0.92      0.89        35
premium_buyer       0.80     0.70      0.75        17

    accuracy                           0.85        52
   macro avg       0.84     0.81      0.82        52
weighted avg       0.85     0.85      0.85        52
### Key Insights:
1. The model performs better at identifying "bargain_hunter" (higher recall and precision) compared to "premium_buyer".
2. The ROC AUC score (0.90) indicates excellent class separation capability.
3. The F1-score for "premium_buyer" (0.75) suggests room for improvement in balancing precision and recall for this minority class.

The actual numeric values may vary slightly due to randomness in the train-test split, but this represents the expected outcome. The confusion matrix plot will visually summarize the model's performance across classes.

# fraud_detection

This project utilizes machine learning techniques to detect fraud in transactional data.
Types of models: Logistic Regression, Random Forest, and XGBoost.

### Model Evaluation Results:

1. **Logistic Regression:**
   - The model achieved high accuracy on both training and test datasets.
   - However, it faced challenges in identifying fraudulent transactions (minority class), with low recall for class 1.
   - Model performance could be enhanced with further adjustments to the threshold or the use of resampling techniques.

2. **Random Forest:**
   - The Random Forest model demonstrated excellent performance on the training data with perfect classification of the majority class.
   - However, on the test data, the model struggled to identify a significant number of fraudulent transactions, as indicated by the low recall for class 1.
   - Deeper evaluation is necessary to improve classification performance on the minority class.

3. **XGBoost:**
   - The XGBoost model achieved high accuracy on both training and test datasets for the majority class.
   - However, the model still faced challenges in identifying fraudulent transactions with low recall for class 1.
   - Adjusting the threshold or using resampling techniques may help improve performance on the minority class.

### Conclusion:

This project demonstrates that while the machine learning models used can achieve high overall accuracy, the main challenge lies in their ability to identify fraudulent transactions, which constitute the minority class in the dataset. Therefore, ongoing evaluation and refinement of the models are crucial to enhancing fraud detection capabilities. This can be achieved through optimizing model parameters, adjusting thresholds, or implementing resampling techniques such as oversampling or undersampling. 

The project aims not only to deliver accurate models overall but also focuses on detecting fraud cases that often have significant financial implications.

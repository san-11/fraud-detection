# fraud-detection
The fraud detection system addresses a dataset with imbalanced classes where 0 represents normal transactions and 1 indicates fraudulent transactions. The skewed distribution of the "isFraud" column can lead to biased model training, favoring non-fraudulent cases. Due to the limited number of fraud cases, an unbalanced relationship emerges between fraud and legitimate transactions. To tackle this, the Random Forest Classifier algorithm is recommended for classification.

Correlations between features such as oldbalanceOrig/newbalanceOrig and oldbalanceDest/newbalanceDest are observed, highlighting the need to either transform or eliminate these columns to prevent bias in the model's predictions.

Three categorical attributes require conversion to numeric values to assess potential multicollinearity. In conclusion, given the dataset's class imbalance, the Random Forest algorithm is ideal for predicting fraudulent transactions. By leveraging multiple decision trees, this approach offers effective calibration and improved accuracy.

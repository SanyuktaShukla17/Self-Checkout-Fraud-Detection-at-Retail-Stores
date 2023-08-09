# Self-Checkout-Fraud-Detection-at-Retail-Stores

Brief abstract of the idea and it’s alignment with the theme:
Retail stores like Walmart have self checkouts for customer convenience and efficiency. However self checkouts come with a risk of fraudulent activities leading to financial losses to the company. The challenge here is to accurately identify the fraudulent activities as well as to avoid putting off false accusations on innocent customers. To address this issue we have come up with a self checkout fraud detection system which will identify fraudulent activities. 

High Level Architecture :
When the customer is using a Self-Checkout System, various factors like number of items, scanned items/unscanned items, total scanning time with respect to number of products , etc can be observed. These features will be used to train a machine learning model. This model will help to identify the patterns and detect if it is a fraud or not. If a fraudulent activity is detected the security person will receive an alert and take further actions. 
Future Scope : To have a double proof of fraud before accusing the customer , we can train a machine learning model to detect fraudulent actions through video clips from cctv surveillance.

Implementation Plan:
Data Loading, Preprocessing and Data Splitting into Train & Test data.
Model Training and Evaluation : We are planning to train the model on machine learning models like : Decision Tree, Random Forest, and Naive Bayes using the training data. The model evaluation metrics will be :  Accuracy, Precision, Recall, F1 Score.
Model Comparison and Visualization : To identify the most effective model for fraud detection we will  visualize and compare their evaluation metrics. 
Hyperparameter Tuning & Final Model Comparison for better precision.
We are planning to create a User Interface using open source python libraries and integrate it with machine learning model to detect frauds.

Impact : This implementation plan is designed to accurately detect frauds at Self-Checkout and help organizations with their financial interest.

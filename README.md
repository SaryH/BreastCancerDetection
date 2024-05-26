Breast Cancer Diagnosis Using Machine Learning

This project focuses on the application of machine learning models for the diagnosis of breast cancer, leveraging a comprehensive dataset of tumor measurements. The primary goal is to accurately classify tumors as malignant (cancerous) or benign (non-cancerous) using advanced machine learning techniques.

Dataset
The dataset utilized in this project, sourced from Kaggle, includes 30 features derived from the digitized images of fine needle aspirates (FNA) of breast masses. It encompasses data from 569 patients, offering a balanced representation of both malignant and benign cases. The dataset is critical in training models to distinguish between the two classes based on detailed tumor measurements.

Models and Methodology

Three machine learning models were implemented and evaluated:

K-Nearest Neighbors (KNN)
XGBoost Classifier
Random Forest Classifier
Model Evaluation Metrics
Precision
Recall
Accuracy
F1 Score
Area Under the Curve (AUC)
Receiver Operating Characteristic (ROC) Curve
These metrics provided a robust assessment of each model's performance in classifying tumors accurately.

Results and Analysis

K-Nearest Neighbors (KNN): Demonstrated limitations in recall and overall accuracy, making it less suitable for this medical diagnosis task.

XGBoost Classifier: Showed high recall for malignant cases, making it effective in identifying true cancer cases.

Random Forest Classifier: Exhibited perfect precision and recall for benign cases, ensuring no malignant tumors were misclassified as benign.

Conclusion

Both XGBoost and Random Forest models achieved impressive results, with a notable trade-off between recall for malignant cases (XGBoost) and precision for benign cases (Random Forest). The choice between models depends on the prioritization of minimizing false negatives or false positives in a clinical setting.

Future Work

For further validation and potential clinical application, a larger and more diverse dataset is necessary. This project underscores the potential of machine learning to aid in medical diagnostics, complementing the expertise of healthcare professionals.

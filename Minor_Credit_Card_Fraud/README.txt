Credit Card Fraud Detection — Minor Project
Model: RandomForestClassifier (200 trees), SMOTE applied only to training data.
Dataset: creditcard.csv fetched from the GitHub CSV URL in the notebook.
Test protocol: stratified 80/20 split, random_state=42; untouched test partition.
The final notebook exports fraud_evaluation_metrics.json after the confusion matrix cell.
This environment could not fetch the dataset because outbound network/DNS is disabled. Therefore no test metrics are fabricated; run all cells in Colab with internet access and copy the JSON values into the report.

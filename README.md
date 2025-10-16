# Cancer-Prediction-using-gene-expression

### Problem Statement:
This project builds a machine learning model to predict whether cancer is present in a patient based on gene expression levels (Gene One and Gene Two). The model classifies patients as:

•	0 → No Cancer Present

•	1 → Cancer Present

It can help in early cancer detection, supporting healthcare professionals in diagnosis and treatment planning.


### Approach & Evaluation:

•	Model: K-Nearest Neighbors (KNN)

• Hyperparameter Tuning: Used GridSearchCV to find the best n_neighbors = 22 and distance metric p = 2

•	Train Accuracy: 93.4%

•	Test Accuracy: 94.9%

•	Cross-Validation Score: 93.5%



### Metrics Used: Accuracy, Confusion Matrix, Cross-Validation, classification_report



### Dataset & Tools Used:

•	Dataset: gene_expression.csv with columns Gene One, Gene Two, Cancer Present

•	Tools: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn


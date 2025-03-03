# Patient-Survival-Prediction
🏥 Patient Survival Prediction in ICU using Machine Learning This project aims to predict patient survival outcomes in Intensive Care Units (ICUs) using machine learning techniques on the MIT GOSSIS dataset, containing over 91,000 patient records. We analyzed critical features such as Age, Gender, APACHE II scores, ventilator status, and other clinical metrics to improve mortality predictions.

🔬 Objectives
Evaluate machine learning models for ICU mortality prediction.
Investigate the impact of age and gender-specific models.
Perform feature selection to identify key clinical indicators.
Analyze subgroup performance (male, female, young, middle-aged, elderly).

⚙️ Methods
Dataset:  MIT GOSSIS ICU Dataset
Size: 91,713 patients
Features: 85 attributes including age, gender, APACHE II score, ventilator status, vital signs, and more.
Target: hospital_death (Binary: 0 = Survived, 1 = Deceased)

Models:
LightGBM
Random Forest
Logistic Regression
Stochastic Gradient Descent (SGD)
K-Nearest Neighbors (KNN)
Tools: df-analyze for automated ML workflow, feature selection, and hyperparameter tuning.
Evaluation: Accuracy, AUC, F1 Score, Balanced Accuracy, Precision, Recall.

📊 Results
Model	Accuracy	AUC	F1 Score	Balanced Accuracy
GANDALF	93.7%	0.902	Best	High
LightGBM	92.9%	0.889	High	Good
RandomForest	92.1%	0.882	Good	Good

🚀 Key Findings:
Age and Gender models revealed unique mortality patterns.
Ethnicity, APACHE II Score, and Glasgow Coma Scale (GCS) were top predictors.
Advanced feature selection boosted model performance.

📁 Project Structure
bash
Copy
Edit
├── data/
│   └── mit_gossis_dataset.csv
├── notebooks/
│   └── data_preprocessing.ipynb
│   └── model_training.ipynb
├── results/
│   └── evaluation_metrics.csv
├── requirements.txt
├── LICENSE
├── README.md
└── main.py


👥 Contributors
Bharath Gopalsamy
Lokesh Janakiraman

#🚦 Traffic Volume Prediction

A machine learning system designed to predict traffic volume using hybrid models combining traditional ML and deep learning. The project integrates feature engineering, data balancing, and hybrid feature selection to achieve high accuracy and robustness.

📌 Features

Hybrid Models: Implemented XGBoost, LSTM, and CNN for prediction.

High Accuracy: Achieved 93.78% accuracy in traffic volume prediction.

Data Balancing: Applied SMOTE to handle class imbalance, improving accuracy by 2–6%.

Feature Engineering:

Time encoding (hour, day, season).

Weather data merging.

Peak-hour tagging.

Hybrid Feature Selection: Combined PCA, RFE, and correlation matrix for optimal feature reduction.

Research Contribution: Work selected for IEEE publication.

🛠️ Technologies Used

Programming Language: Python

Libraries & Frameworks:

Machine Learning: Scikit-learn, XGBoost

Deep Learning: TensorFlow/Keras

Data Processing: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Resampling: SMOTE (Imbalanced-learn)

📊 Workflow

Data Collection & Preprocessing

Cleaned and merged weather and traffic datasets.

Applied normalization and encoding.

Feature Engineering

Extracted time-based features (hour, weekday, holiday).

Integrated weather conditions.

Tagged peak/off-peak hours.

Feature Selection

PCA for dimensionality reduction.

RFE for feature ranking.

Correlation Matrix for multicollinearity removal.

Model Training

Trained hybrid models (XGBoost, LSTM, CNN).

Hyperparameter tuning via GridSearch/RandomSearch.

Model Evaluation

Accuracy, Precision, Recall, F1-score.

Achieved 93.78% accuracy.

📈 Results

Hybrid model outperformed baseline ML models.

SMOTE improved minority class representation, boosting accuracy by 2–6%.

Research recognized and selected for IEEE publication.

🚀 Future Improvements

Real-time traffic volume prediction using live IoT sensor feeds.

Integration with navigation systems for intelligent traffic management.

Deployment via Flask/FastAPI for API-based prediction service.

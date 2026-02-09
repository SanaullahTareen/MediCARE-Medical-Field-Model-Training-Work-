Medicare-AI: Intelligent Diabetes Management Systems
Medicare-AI is a dual-model machine learning framework designed to provide clinical decision support for Type 1 Diabetes management. Utilizing the OhioT1DM clinical dataset, this project implements both deep learning and ensemble learning techniques to predict glucose trends and optimize insulin dosage recommendations.

## Key Components
1. Glucose Trend Forecasting (Deep Learning)
Architecture: Long Short-Term Memory (LSTM) Neural Networks.

Function: Performs time-series analysis on continuous glucose monitoring (CGM) data.

Objective: Provides a 30-minute predictive horizon to help patients preemptively manage hyperglycemic or hypoglycemic events.

2. Personalized Insulin Advisor (Ensemble Learning)
Architecture: XGBoost Classifier.

Function: A multi-modal classification model that processes glucose history, carbohydrate intake, and physical activity levels.

Objective: Delivers actionable clinical insights by recommending whether to Increase, Decrease, or Maintain current insulin dosages.

### Technical Stack
Languages: Python 3.x

Deep Learning: TensorFlow / Keras (LSTM)

Machine Learning: XGBoost, Scikit-learn

Data Processing: Pandas, NumPy

Visualization: Matplotlib, Seaborn

### Dataset
The models are trained and validated on the OhioT1DM Dataset, a high-fidelity clinical dataset containing 8 weeks of data for multiple contributors, including CGM, insulin, life events, and physiological data.

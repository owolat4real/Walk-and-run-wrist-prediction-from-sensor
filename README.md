Human Activity Recognition Analysis

This project uses wrist-based sensor data (acceleration, gyroscope, wrist used, and time features) to classify Walking (0) vs Running (1).

Key Observations

Acceleration & Gyroscope: Mostly centered around zero; spikes indicate sudden movements. Z-axis shows largest variations.

Wrist Sensor: 52.2% right wrist, 47.8% left wrist.

Time Features: Most data recorded in June–July 2017.

Activity Label: Balanced binary classes, suitable for classification.

Feature Importance

Wrist (left/right)

Acceleration (x, y, z)

Gyroscope (x-axis)

Day and month

Movement and time-based features are strong predictors of activity.

Model Performance
Model	Accuracy
ANN	99.68%
MLPClassifier	99.31%
SVC	97%
Tensor Neural Network	43.7%

Conclusion: ANN is the most accurate and reliable model.

Insights & Challenges

Overfitting handled via careful feature selection and model tuning.

Domain knowledge crucial for interpreting sensor data.

Dataset is balanced, reliable, and suitable for activity recognition modeling.

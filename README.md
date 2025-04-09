🏋️‍♂️ Human Movement Classification using XGBoost
This project implements machine learning models to classify bicep and squat movements based on motion data. The models are trained using XGBoost and evaluated using multiple classification metrics.

📁 Datasets
bicep_train.csv / bicep_test.csv

Labels: C (contracted), L (loose) → mapped to 1 and 0

squat_train.csv / squat_test.csv

Labels: up, down → mapped to 1 and 0

📊 Features
Motion data (e.g., angles, positions — format depends on your CSV)

Binary classification using XGBoost

Model evaluation through:

Accuracy

Precision, Recall, F1 Score

Confusion Matrix Heatmaps

🛠️ Models Used
XGBoost Classifier

n_estimators = 100

learning_rate = 0.1

max_depth = 5

objective = binary:logistic

✅ Results
BICEP Model
Accuracy: ~X.XXXX

Precision: ~X.XXXX

Recall: ~X.XXXX

F1 Score: ~X.XXXX

Confusion Matrix:

Predicted vs Actual for C (1) and L (0)

SQUAT Model
Accuracy: ~X.XXXX

Precision: ~X.XXXX

Recall: ~X.XXXX

F1 Score: ~X.XXXX

Confusion Matrix:

Predicted vs Actual for up (1) and down (0)

📈 Visualizations
Confusion matrices are plotted using Seaborn heatmaps.

🧠 Future Improvements
Hyperparameter tuning with GridSearchCV

Cross-validation

Integration with real-time pose estimation (OpenPose/MediaPipe) for live movement detection

Feature importance visualization


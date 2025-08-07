# Diabetes-Prediction-App-Machine-Learning
 A Streamlit web app that predicts diabetes risk using machine learning (SVM classifier). Includes model training, deployment, and user-friendly interface.

🚀 **Live Demo**: [Test the App Here](https://diabetes-prediction-app-machine-learning-zxmxslmgwo8jjdrsohzj5.streamlit.app/)

# Diabetes Prediction API

🚀 **Live API**: [https://diabetes-api.onrender.com](https://diabetes-prediction-app-machine-learning.onrender.com)

## How to Use

### Make a Prediction
```bash
curl -X POST "https://diabetes-prediction-app-machine-learning.onrender.com/diabetes_prediction" \
-H "Content-Type: application/json" \
-d '{
  "pregnancies": 2,
  "Glucose": 120,
  "BloodPressure": 70,
  "SkinThickness": 30,
  "Insulin": 80,
  "BMI": 25.5,
  "DiabetesPedigreeFunction": 0.5,
  "Age": 35
}'

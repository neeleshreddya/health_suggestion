# Personalized Healthcare Recommendations Using Deep Learning

This project uses a neural network model built with TensorFlow/Keras to predict the likelihood of diabetes in individuals based on health parameters. It then provides personalized healthcare recommendations based on the predicted risk level.

## Dataset
The model is trained on a diabetes prediction dataset containing features like age, gender, hypertension, heart disease, BMI, HbA1c level, blood glucose level, and smoking history.

## Project Highlights
- Data preprocessing including encoding and normalization.
- Neural network model training and evaluation.
- Real-time healthcare recommendations by patient serial number.
- Accuracy visualization and classification metrics.

## Dependencies
Install required packages using:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository.
2. Place `diabetes_prediction_dataset.csv` in the root directory.
3. Run the Python script.

You will be prompted to enter a serial number (row index) to get prediction and recommendation for a specific individual in the dataset.

## Sample Output

```
Enter the serial number (row index) of the person: 15

👤 Person at Serial Number 15:
gender                  1.0
age                   56.0
hypertension            0.0
heart_disease           1.0
smoking_history         3.0
bmi                    26.8
HbA1c_level             6.5
blood_glucose_level   170.0
diabetes                1.0

🧪 Predicted Diabetes Probability: 0.91
💡 Healthcare Recommendation: 🔴 High Risk: Immediate consultation and medical attention advised.
```

---

## Author
- Developed using Python, Pandas, Scikit-learn, and TensorFlow.

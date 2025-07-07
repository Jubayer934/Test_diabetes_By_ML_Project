
# 🩺 Diabetes Prediction Web App

This is a machine learning-powered web application that predicts the likelihood of diabetes based on user input. The model was trained using the Pima Indian Diabetes dataset and deployed using Flask and Render.

🔗 **Live App URL**: [https://test-diabetes-by-ml-project.onrender.com/](https://test-diabetes-by-ml-project.onrender.com/)

---

## 📊 Dataset
- Source: Pima Indian Diabetes Dataset
- Features used:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
- Target:
  - Outcome (0 = No Diabetes, 1 = Diabetes)

---

## 🚀 Technologies Used

| Layer        | Technology         |
|--------------|--------------------|
| ML Model     | GradientBoostingClassifier (scikit-learn) |
| Web Framework| Flask              |
| Deployment   | Render             |
| Frontend     | HTML, CSS          |
| Serialization| Joblib             |

---

## 🛠️ How It Works

1. User enters 8 medical input values through a web form.
2. Flask sends the input to a backend Python server.
3. The server loads the pretrained model (`model.pkl`).
4. A prediction is made (0 or 1), along with probability (confidence %).
5. The result is shown on the webpage.

---


## 🌐 Deployment

This project is deployed on [Render](https://render.com/), a free hosting service for web apps.


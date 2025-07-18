# Wall-Following-Robot
# 🤖 Wall Following Robot Simulation using ML Classifiers

This project implements a machine learning approach to classify and simulate a **Wall-Following Robot** using real sensor data. The robot uses sensory inputs to determine how it should navigate its environment by following walls or avoiding obstacles.

The model is trained on a labeled dataset and various classifiers are evaluated to determine the best one for accurate movement prediction.

---

## 📂 Dataset

- The dataset (`Robo.csv`) contains input from robot sensors and corresponding labeled movement directions.
- Target variable: `V1` (movement label — forward, left, right, etc.)
- Features: Distance or direction data from various sensors.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**, **NumPy** – data manipulation
- **Matplotlib** – data visualization
- **Scikit-learn** – model training and evaluation (Logistic Regression, SVM, KNN)
- **TensorFlow/Keras** – for potential deep learning model integration

---


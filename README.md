# 🔮 Customer Churn Prediction using ANN (TensorFlow & Keras)

## 📌 Overview

This project predicts whether a customer will leave (churn) or stay with a company using an **Artificial Neural Network (ANN)** built with TensorFlow and Keras.

Customer churn prediction is a key problem in business analytics, helping companies **retain customers and reduce losses**.

---

## 🚀 Features

* Data preprocessing using Pandas & NumPy
* Handling categorical variables (Label Encoding + One-Hot Encoding)
* Feature scaling using StandardScaler
* ANN model built with TensorFlow/Keras
* Model evaluation using confusion matrix & accuracy
* Visualization of training performance (accuracy graph)

---

## 🧠 Tech Stack

* Python 🐍
* NumPy
* Pandas
* Scikit-learn
* TensorFlow / Keras
* Matplotlib

---

## 📂 Dataset

* Dataset used: `Churn_Modelling.csv`
* Contains customer details such as:

  * Credit Score
  * Geography
  * Gender
  * Age
  * Balance
  * Estimated Salary
  * Exited (Target Variable)

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing

* Load dataset using Pandas
* Select features (X) and target (y)
* Encode categorical variables:

  * Label Encoding (Gender)
  * One-Hot Encoding (Geography)
* Split dataset into training & testing sets
* Apply feature scaling

---

### 2️⃣ Model Building (ANN)

* Sequential Neural Network
* 2 Hidden Layers (ReLU activation)
* Output Layer (Sigmoid activation)

---

### 3️⃣ Model Compilation

* Optimizer: Adam
* Loss Function: Binary Crossentropy
* Metric: Accuracy

---

### 4️⃣ Model Training

* Epochs: 50
* Batch Size: 32
* Validation Split: 20%

---

### 5️⃣ Evaluation

* Confusion Matrix
* Accuracy Score

---

### 6️⃣ Visualization

* Training vs Validation Accuracy Graph

---

## 📊 Results

* Achieved good accuracy on test data
* Model performance visualized using accuracy curves
* Helps identify overfitting/underfitting

---

## 📈 Sample Graph

<img width="573" height="451" alt="Churn_Prediction_graph" src="https://github.com/user-attachments/assets/810c2afd-9308-4139-9430-b00781bc54d1" />


---

## 🛠️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/your-username/customer-churn-ann.git

# Navigate to project folder
cd customer-churn-ann

# Install dependencies
pip install -r requirements.txt

# Run the project
python main.py
```

---

## 📁 Project Structure

```
├── Churn_Modelling.csv
├── main.py
├── README.md
├── requirements.txt
```

---

## 🎯 Future Improvements

* Hyperparameter tuning
* Use Dropout to reduce overfitting
* Try other models (Random Forest, XGBoost)
* Deploy model using Flask/Streamlit

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

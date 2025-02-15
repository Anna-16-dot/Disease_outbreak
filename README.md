# 🏥 Disease Outbreak Prediction System  

## 📌 Overview  
This project is a **Machine Learning-based web application** built with **Streamlit** that predicts the likelihood of **Diabetes, Parkinson’s, and Heart Disease**.  
It utilizes **Support Vector Machine (SVM)** models to analyze patient data and provide predictions.  

## 🚀 Features  
✅ **Diabetes Prediction** - Detects diabetes risk based on medical parameters.  
✅ **Heart Disease Prediction** - Evaluates heart disease probability.  
✅ **Parkinson’s Disease Prediction** - Identifies early signs of Parkinson’s.  
✅ **Interactive Web UI** - Simple and user-friendly interface using **Streamlit**.   

## 📂 Project Structure  
```
disease-prediction/
│-- saved_models/
│   │-- diabetes_model.sav
│   │-- heart_disease_model.sav
│   │-- parkinsons_model.sav
│
│-- .gitignore
│-- README.md
│-- app.py
│-- requirements.txt
```

## 🛠 Installation  

### 🔹 Clone the repository  
```sh
git clone https://github.com/yourusername/disease-prediction.git
cd disease-prediction
```

### 🔹 Install dependencies  
```sh
pip install -r requirements.txt
```

### 🔹 Run the application  
```sh
streamlit run app.py
```

## 📜 Requirements  
Ensure you have the following Python libraries installed:  
```sh
numpy==1.26.3  
scikit-learn==1.3.2  
streamlit==1.29.0  
streamlit-option-menu==0.3.6  
```

## 🏆 Usage  
1️⃣ Run the app using **Streamlit**.  
2️⃣ Select **Diabetes, Heart Disease, or Parkinson's Prediction** from the sidebar.  
3️⃣ Enter the required health parameters.  
4️⃣ Click the **Predict** button to see the results.  

## 🤖 Machine Learning Model  
This project leverages **Support Vector Machine (SVM)** models trained on medical datasets for accurate disease classification.  

## 🤝 Contributing  
🔹 Fork the repository  
🔹 Create a new branch (`git checkout -b feature-branch`)  
🔹 Commit your changes (`git commit -m "Added new feature"`)  
🔹 Push to the branch (`git push origin feature-branch`)  
🔹 Create a Pull Request  

## 👨‍💻 Author  
Developed by **Joice Anna Jecob**  

# disease_prediction

This is an open source project
# 🏥 Disease Prediction System using Machine Learning

![Streamlit](https://img.shields.io/badge/Streamlit-ML%20Web%20App-red)
![Python](https://img.shields.io/badge/Python-3.11-blue)
![GitHub](https://img.shields.io/badge/GitHub-Repository-lightgrey)

## 📌 Overview  
This project is an AI-powered Disease Prediction System that uses machine learning models to predict the likelihood of Diabetes, Heart Disease, and Parkinson’s Disease** based on user-input medical parameters.

The system is built with Python, Streamlit, and Scikit-learn, offering an interactive web interface for real-time predictions.


## 🛠️ Features  
✅ Predicts Diabetes, Heart Disease, and Parkinson’s Disease 
✅ Uses trained ML models for fast & accurate predictions  
✅ Streamlit Web App for an easy-to-use interface  
✅ Deployed on GitHub & Streamlit Cloud for accessibility  


## 📂 Project Structure  

📂 disease_prediction
 ├── 📂 datasets                # Medical datasets for training
 │   ├── diabetes.csv
 │   ├── heart.csv
 │   ├── parkinsons.csv
 │
 ├── 📂 training_modules        # Trained ML models
 │   ├── diabetes_model.sav
 │   ├── heart_model.sav
 │   ├── parkinsons_model.sav
 │
 ├── 📂 web_app                 # Streamlit application files
 │   ├── web.py
 │
 ├── requirements.txt           # Required dependencies
 ├── README.md                  # Project documentation
 ├── .gitignore                 # Files to ignore in GitHub


## 🚀 Running the Web Application  
Run the Streamlit app using:  
```sh
streamlit run web.py
```
After running, open the browser and go to:  
👉 http://localhost:8501

## 🖥️ Deployment  
The app is deployed on Streamlit Cloud. You can access it at:  
🔗 [Live App on Streamlit](https://share.streamlit.io/your-username/disease_prediction/main/web.py)


## 🔬 Machine Learning Models  
The system uses trained ML models for disease prediction:  
- Diabetes Model → Trained on Pima Indians Diabetes Dataset
- Heart Disease Model → Trained on Cleveland Heart Disease Dataset
- Parkinson’s Model → Trained on **Parkinson’s Voice Dataset  



## 📌 Future Improvements  
- 🏥 Add More Diseases (e.g., Lung Cancer, Stroke)  
- 📊 Improve Model Accuracy using Deep Learning  
- 📡 Real-Time Data Integration from IoT & Wearables  
- 🤖 Chatbot Integration for Health Advice  




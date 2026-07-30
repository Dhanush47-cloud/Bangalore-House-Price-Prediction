# 🏠 Bengaluru House Price Prediction

A Machine Learning-powered web application that predicts house prices in Bengaluru based on property features such as location, total square footage, number of bedrooms (BHK), and bathrooms. The application is built using **Python**, **Streamlit**, and **Scikit-learn** with an interactive user interface and animated components. :contentReference[oaicite:0]{index=0}

---

## 📸 Application Preview           

                

### Home Page                          
<img width="1364" height="595" alt="Screenshot 2026-07-22 110758" src="https://github.com/user-attachments/assets/0df46976-e13e-43a4-9fef-6ff2b94a5850" />


### Prediction Page
<img width="1365" height="585" alt="Screenshot 2026-07-22 110841" src="https://github.com/user-attachments/assets/1e84b913-07c0-440c-9b6f-c153c28fe724" />


---

## 🚀 Features

- 🏡 Interactive Streamlit web application
- 📍 Location-based house price prediction
- 📐 Predict using area (square feet)
- 🏠 Select BHK and bathrooms
- 💰 Instant house price estimation
- 🎨 Attractive UI with Lottie animations
- ⚡ Fast prediction using a trained Random Forest model

---

## 🛠 Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### Machine Learning
- Scikit-learn
- Random Forest Regressor

### Libraries Used
- NumPy
- Pandas
- Pickle
- Streamlit Lottie
- JSON

---

## 📂 Project Structure

```
Bangalore_House_price/
│
├── app.py
├── RFmodel.pkl
├── cleaned_df.csv
├── Bengaluru_House_Datastudent.csv.xlsx
├── requirements.txt
├── home_anime.json
├── loading_anime.json
├── icons/
│   └── house_logo.jpeg
└── house_price_prediction.ipynb
```

---

## 📊 Dataset

The model is trained using the Bengaluru House Price Dataset containing information such as:

- Location
- Total Square Feet
- Number of Bedrooms (BHK)
- Number of Bathrooms
- House Price

The data is cleaned and preprocessed before training the machine learning model.

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Random Forest Regressor

### Input Features

- Location
- Total Square Feet
- Number of Bathrooms
- Number of BHK

### Output

- Estimated House Price (INR)

---

## 💡 How It Works

1. Launch the Streamlit application.
2. Navigate to the **Predict Price** page.
3. Select:
   - Location
   - Total Square Feet
   - BHK
   - Bathrooms
4. Click **Predict Price**.
5. The trained Random Forest model predicts the estimated property price and displays it instantly. :contentReference[oaicite:1]{index=1}

---

## 🎯 Learning Outcomes

This project helped me learn:

- Data Cleaning
- Feature Engineering
- Machine Learning
- Random Forest Regression
- Streamlit Application Development
- Model Deployment
- UI Design

---


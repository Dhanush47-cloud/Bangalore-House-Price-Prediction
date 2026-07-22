# 🏠 Bengaluru House Price Prediction

A Machine Learning-powered web application that predicts house prices in Bengaluru based on property features such as location, total square footage, number of bedrooms (BHK), and bathrooms. The application is built using **Python**, **Streamlit**, and **Scikit-learn** with an interactive user interface and animated components. :contentReference[oaicite:0]{index=0}

---

## 📸 Application Preview

> Add screenshots of your application here.

### Home Page
![Home Page](images/home.png)

### Prediction Page
![Prediction Page](images/predict.png)

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

## ⚙ Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/Bangalore-House-Price-Prediction.git
```

### Navigate to project folder

```bash
cd Bangalore-House-Price-Prediction
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
streamlit run app.py
```

---

## 📦 Requirements

```
streamlit
streamlit-lottie
numpy
pandas
scikit-learn
plotly
```

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

## 📈 Future Improvements

- Add Price Distribution Graphs
- Deploy on Streamlit Cloud
- Interactive Maps
- Compare House Prices
- Recommendation System
- User Authentication
- Save Prediction History

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

## 👨‍💻 Author

**Dhanush Bangera**

- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!

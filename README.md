# 🏡 Bangalore House Price Prediction

A machine learning project to predict house prices in Bangalore using regression techniques. This project demonstrates the end-to-end ML pipeline: from data preprocessing and model training to deployment with a simple web interface.

---

## 📌 Features

- Preprocesses raw housing data (location, size, sqft, bathrooms, etc.)
- Implements regression models (Linear Regression, Lasso, Ridge, Decision Trees, etc.)
- Saves trained model using pickle
- REST API built with Flask (`server.py`)
- Frontend using HTML, CSS, JavaScript
- User can enter house details and get predicted price instantly

---

## 📂 Project Structure



.
├── app.css # Frontend styling
├── app.html # Webpage interface
├── app.js # Client-side JS logic
├── banglore_home_prices_model.pickle # Trained ML model
├── bengaluru_house_prices.xls # Dataset
├── columns.json # Metadata about features/columns
├── server.py # Flask server (backend API)
├── util.py # Utility functions for prediction
├── Untitled.ipynb # Jupyter notebook (EDA + model building)
└── README.md # Project documentation


---

## ⚙️ Installation

**Clone the repository:**
```bash
git clone https://github.com/suhaniijjaiiin/BangaloreHousePricePrediction.git
cd BangaloreHousePricePrediction


Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate


Install dependencies:

pip install -r requirements.txt


(If you don’t have requirements.txt, add: Flask, scikit-learn, pandas, numpy, matplotlib, jupyter)

▶️ Usage

Run the Flask server

python server.py


Server will start at: http://127.0.0.1:5000/

Open frontend
Open app.html in a browser to interact with the model.

Jupyter Notebook
To explore data preprocessing and model training:

jupyter notebook Untitled.ipynb

📊 Dataset

Source: Kaggle Bangalore House Prices dataset

Attributes: location, sqft, number of bathrooms, number of BHK, price, etc.


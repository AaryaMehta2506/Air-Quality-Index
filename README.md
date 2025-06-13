# 🌍 Air Quality Index (AQI) Prediction Web App

This project combines **environmental sensing**, **data science**, and **machine learning** to predict the Air Quality Index (AQI) for a given location. It features a **Flask-based** web interface and uses **historical pollutant data** and **meteorological parameters** for predictions.

---

## 🚀 Features

- 🌤️ **Real-time AQI Prediction**: Input live pollutant values (PM2.5, PM10, NO₂, etc.) to get AQI estimates.
- 📊 **Historical Data Analysis**: Explore trends and patterns using Jupyter notebooks.
- 🤖 **Multiple ML Models**: Includes regression models like Linear Regression, Random Forest, and XGBoost.
- 🌐 **Flask Web App**: Users can interact with the model through an easy-to-use web form.
- 📈 **Model Visualization**: Inspect model performance (RMSE, R²) in Jupyter Notebook.
- ⚙️ **Model Persistence**: Saved trained models for quick deployment.

---

## 🗂️ Project Structure

Air-Quality-Index/
├── app.py # Flask web application
├── requirements.txt # Project dependencies
├── data/ # Cleaned and raw AQI datasets
├── notebooks/ # Jupyter notebooks for analysis + model training
├── models/ # Serialized ML models (e.g., .pkl or .joblib)
├── templates/ & static/ # Front‑end (HTML, CSS, JS)
├── README.md # Project overview and instructions
└── LICENSE # MIT License file


---

## ⚙️ Setup Instructions

### 1. 🔄 Clone the Repository

```
git clone https://github.com/AaryaMehta2506/Air-Quality-Index.git
cd Air-Quality-Index
```

2. 🧪 Create a Virtual Environment
```
python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate
```
3. 📦 Install Dependencies
```
pip install -r requirements.txt
```
4. 🚀 Run the Flask App
```
python app.py
```
Then visit http://127.0.0.1:5000/ in your browser.

# 📊 Model Training & Evaluation
To retrain the model or evaluate its performance:

Open the notebooks in notebooks/ (e.g., AQI_Model_Training.ipynb).

Load and preprocess data.

Train regression models and review evaluation metrics.

Save your trained model (e.g., in models/).

# 💡 Example Use Case
Input pollutant values:

PM2.5 = 85

PM10 = 120

NO₂ = 40
Output:

# 📍 Predicted AQI: 160 (Unhealthy)

📈 Model accuracy: RMSE = 15.2, R² = 0.82

# 🤝 Contributing
Contributions are welcome! To get started:

Fork the repository

Create a feature branch (git checkout -b feature-xyz)

Commit your changes (git commit -m 'Add feature')

Push and open a pull request

# 📄 License
This project is licensed under the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE).



## 👩‍💻 Author

**Aarya Mehta**  
🔗 [GitHub Profile](https://github.com/AaryaMehta2506)

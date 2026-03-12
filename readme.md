# 🌍 London Air Pollution Forecasting

A machine learning project that predicts **Nitrogen Dioxide (NO₂) air pollution levels in London** using environmental and weather-related data.
The project analyzes historical pollution trends and builds predictive models to estimate future air quality levels.

Air pollution is a major environmental and health issue in large cities. London has multiple monitoring stations that record pollutant concentrations and environmental conditions. This project uses that data to train a machine learning model capable of forecasting NO₂ pollution levels.

---

# 📊 Project Overview

The main objective of this project is to explore London’s air pollution data and build a predictive model to forecast NO₂ concentrations.

This project includes:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Pollution trend visualization
* Machine learning model training
* Model evaluation
* Feature importance analysis
* Model persistence using Joblib

The trained model can help estimate pollution levels based on environmental variables such as weather conditions and other pollutants.

---

# 📂 Project Structure

```
london_airpollution_forecast
│
├── data/                # Dataset files
├── notebooks/           # Jupyter notebooks for analysis and experiments
├── models/              # Saved machine learning models
├── src/                 # Python scripts
│
├── requirements.txt     # Project dependencies
├── README.md            # Project documentation
└── main.ipynb           # Model training notebook
```

---

# 📦 Dataset

The dataset contains historical **London air quality measurements**, including pollutant concentrations and environmental variables collected from monitoring stations.

Example features include:

* NO₂ (Nitrogen Dioxide)
* PM2.5
* PM10
* Temperature
* Humidity
* Wind Speed
* Date / Time

These variables help the machine learning model learn patterns in pollution levels and make predictions.

---

# ⚙️ Technologies Used

This project was built using the following technologies:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Joblib

---

# 🧠 Machine Learning Model

The project uses **XGBoost Regression** to predict NO₂ levels.

The machine learning workflow includes:

1. Data preprocessing
2. Train/test dataset splitting
3. Model training
4. Model evaluation
5. Feature importance analysis
6. Model saving for future use

Example model saving code:

```python
import joblib

joblib.dump(model, "models/xgboost_no2_predictor.pkl")
```

---

# 📈 Visualizations

The project generates several visualizations to understand pollution patterns and model performance:

* NO₂ pollution trend over time
* Feature importance graphs
* Actual vs Predicted pollution values
* Residual error plots

These visualizations help evaluate how well the model performs and which features influence predictions the most.

---

# 🧪 Model Evaluation

Model performance is evaluated using common regression metrics:

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

These metrics measure how accurately the model predicts pollution levels compared to actual values.

---

# ▶️ How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/yathvik/london_airpollution_forecast.git
cd london_airpollution_forecast
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Launch the notebook

```
jupyter notebook
```

Open the main notebook and run all cells to reproduce the analysis and train the model.

---

# 📌 Future Improvements

Possible future enhancements for this project include:

* Implement deep learning models (LSTM / GRU) for time-series forecasting
* Add real-time pollution prediction
* Build an interactive dashboard
* Integrate live weather APIs
* Deploy the model using Streamlit or FastAPI

---

# 🤝 Contributing

Contributions are welcome.
Feel free to open issues or submit pull requests to improve the project.

---

# 📜 License

This project is licensed under the **MIT License**.

---

⭐ If you found this project helpful, consider giving the repository a star.

🌍 Air Quality Index (AQI) Prediction Using Machine Learning

📌 Project Overview

This project aims to predict the Air Quality Index (AQI) using machine learning algorithms based on historical air pollution data. By analyzing pollutant levels such as PM2.5, PM10, CO, NO₂, SO₂, and O₃, the model forecasts AQI values to help in environmental monitoring and decision-making.

🚀 Features

✅ Predict AQI based on pollutant concentration data
✅ Implements Random Forest, Decision Tree, Linear Regression, and KNN algorithms
✅ Data preprocessing, feature selection, and model optimization
✅ Visualization of AQI trends using Matplotlib & Seaborn
✅ Performance evaluation using MSE, RMSE, and R² score


🛠 Technologies Used
Programming Language: Python 🐍
Machine Learning Libraries: Scikit-learn, Pandas, NumPy
Visualization Tools: Matplotlib, Seaborn
Data Handling: CSV, Excel
📂 Dataset
The dataset used in this project consists of historical air pollution records obtained from:

AQI Databases
It includes pollutant levels (PM2.5, PM10, CO, NO₂, SO₂, O₃) and AQI values.

📊 Methodology
1️⃣ Data Collection – Obtain AQI data from public sources.
2️⃣ Preprocessing – Handle missing values, normalize data, and perform feature selection.
3️⃣ Model Selection – Train multiple ML models (Random Forest, Decision Tree, Linear Regression, KNN).
4️⃣ Evaluation – Measure performance using MSE, RMSE, and R² score.
5️⃣ Prediction & Visualization – Predict AQI and visualize trends.

🔥 How to Run the Project
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/Prasanthkumar2004/AQL-Prediction-Model.git
cd AQI-Prediction-ML

2️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt

3️⃣ Run the Jupyter Notebook
bash
Copy
Edit
jupyter notebook

4️⃣ Execute the Python Script
bash
Copy
Edit
python aqi_prediction.py

📈 Results & Performance

Random Forest performed best with the lowest RMSE and highest R² score.
Visualized trends show seasonal variations in AQI levels.
Predictions align with real-world air quality fluctuations.
💡 Future Enhancements
🔹 Implement Deep Learning (LSTMs, CNNs) for better predictions
🔹 Integrate real-time AQI data from APIs
🔹 Deploy as a web-based AQI prediction too

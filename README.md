# Heart Stroke Prediction

A machine learning web application that predicts the risk of heart disease based on clinical parameters. Built with **Streamlit** and powered by a **K-Nearest Neighbors (KNN)** model.

## Live Demo

[Try the app on Streamlit Cloud](https://heart-stroke-prediction.streamlit.app)

## Features

- Interactive web interface for inputting patient health data
- Real-time heart disease risk prediction
- Powered by a trained KNN classifier with feature scaling

## Input Parameters

| Parameter                   | Description                                      |
| --------------------------- | ------------------------------------------------ |
| **Age**                     | Patient's age (18–100)                           |
| **Sex**                     | Male (M) / Female (F)                            |
| **Chest Pain Type**         | ATA, NAP, TA, or ASY                             |
| **Resting Blood Pressure**  | Resting BP in mm Hg (80–200)                     |
| **Cholesterol**             | Serum cholesterol in mg/dL (100–600)             |
| **Fasting Blood Sugar**     | Whether fasting blood sugar > 120 mg/dL (0 or 1) |
| **Resting ECG**             | Normal, ST, or LVH                               |
| **Max Heart Rate**          | Maximum heart rate achieved (60–220)             |
| **Exercise-Induced Angina** | Yes (Y) / No (N)                                 |
| **Oldpeak**                 | ST depression induced by exercise (0.0–6.0)      |
| **ST Slope**                | Up, Flat, or Down                                |

## Tech Stack

- **Python**
- **Streamlit** — Web framework
- **Pandas** — Data manipulation
- **Scikit-learn** — Machine learning model (KNN)
- **Joblib** — Model serialization

## Project Structure

```
Heart-Stroke-Prediction/
├── app.py                  # Streamlit application
├── knn_heart_model.pkl     # Trained KNN model
├── heart_scaler.pkl        # Fitted StandardScaler
├── heart_columns.pkl       # Expected feature columns
├── requirements.txt        # Python dependencies
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.9+

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Saqibb786/Heart-Stroke-Prediction.git
   cd Heart-Stroke-Prediction
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**
   ```bash
   streamlit run app.py
   ```

The app will open in your browser at `http://localhost:8501`.

## Author

**Saqib** — [GitHub](https://github.com/Saqibb786)

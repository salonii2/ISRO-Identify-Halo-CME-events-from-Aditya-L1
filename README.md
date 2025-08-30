### 🌌 SolarGuard-X

Real-time Halo CME (Coronal Mass Ejection) Detection & Prediction
ISRO Hack2Vision 2025 – Problem Statement 10

## 📖 Overview

SolarGuard-X is a machine learning–driven solution to identify Halo CME events based on particle data from the SWIS-ASPEX Payload onboard Aditya-L1.
Our system provides real-time detection, precursor analysis, and visualization to support heliophysics research and enhance space weather forecasting.

### 🚀 Key Features

⚡ Real-time CME Precursor Detection using contrastive learning.

📊 Streaming Data Pipeline for handling continuous solar wind & particle flux data.

🌍 Heliospheric Vector Field Modeling to analyze CME trajectories.

📈 Interactive Dashboard for live monitoring, anomaly detection, and historical comparisons.

🛰️ Integration with ISRO’s Aditya-L1 SWIS-ASPEX Data (flux, density, speed, temperature).

### 📂 Dataset

Primary Data: SWIS Level-2 particle data (Flux, Number Density, Temperature, Speed).

Secondary Data: CACTus CME Catalog (for validation & comparison).

Preprocessing: Cleaning, time-series alignment, normalization.

### 🏗️ Architecture
flowchart TD
  A[SWIS-ASPEX Data Stream] --> B[Preprocessing & Feature Engineering]
  B --> C[Contrastive Learning Model]
  C --> D[Real-time CME Detection]
  D --> E[Heliospheric Vector Modeling]
  E --> F[Visualization Dashboard]

### 🛠️ Tech Stack

Languages: Python, C++

ML/DL: PyTorch, Scikit-learn

Data Pipeline: Apache Kafka, Spark Streaming

Visualization: Plotly, Dash / React + Recharts

Deployment: Docker, FastAPI, Streamlit

### 📊 Dashboard Features

🔍 Live CME precursor detection

⏳ Time-series analysis of solar wind data

🌐 Vector field maps for CME propagation

📜 Historical data comparison with CACTus catalog

### 📌 Use Cases

🛰️ Space Weather Forecasting: Early detection of hazardous solar events.

⚡ Satellite Safety: Protect communication & navigation satellites.

🛡️ Astronaut Protection: Radiation risk assessment.

🌍 Power Grid Management: Mitigate geomagnetic storm impacts.

### 📅 Roadmap

✅ Dataset preprocessing & validation

✅ ML model prototyping (contrastive learning)

🔄 Real-time streaming integration

🔄 Dashboard deployment

### 📜 License

This project is developed exclusively for ISRO Hack2Vision 2025 and is intended for research & demonstration purposes.

✨ SolarGuard-X: Guarding Earth from Solar Storms 🌍☀️

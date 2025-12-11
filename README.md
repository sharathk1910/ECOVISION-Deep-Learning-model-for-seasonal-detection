ECOVISION: Deep Learning Model for Seasonal Detection

A multimodal Deep Learning system that predicts the current season using plant/tree images and environmental parameters such as temperature, humidity, precipitation, wind speed, soil moisture, and more.
This project integrates CNN-based image analysis with machine learning on climatic data to create an accurate environmental prediction model.

📌 Project Overview

Seasonal changes affect agriculture, ecology, biotechnology research, and environmental monitoring. Traditional methods rely on manual observation or climate-only data, leading to errors and inconsistent results.

ECOVISION solves this by combining:
✔ Visual plant features using CNN
✔ Environmental parameters using ML models
✔ Fusion layer to improve prediction accuracy

🎯 Objectives
Primary Goal

Build an AI model that predicts the season by combining plant/tree images and environmental data.

Supporting Objectives

Assist biotechnology and plant science research.

Improve ecological and environmental monitoring.

Provide a learning tool for students and researchers.

Achieve higher accuracy than single-input models.

🧠 Methodology (Proposed System)

The ECOVISION system consists of:

1️⃣ Image Processing Module

Upload plant/tree image

CNN extracts:

Leaf texture

Color variation

Dryness level

Flowering/fruiting stages

2️⃣ Environmental Parameter Module

Processes:

Temperature

Humidity

Precipitation

Wind speed

Atmospheric pressure

Soil moisture

Cloud visibility

Solar radiation

3️⃣ Feature Fusion Layer

Combines outputs from both modules for improved accuracy.

4️⃣ Output

Predicted Season

Confidence Score

📂 Project Structure
ECOVISION/
│── dataset/
│── models/
│── notebooks/
│── src/
│   ├── image_model.py
│   ├── climate_model.py
│   ├── fusion_model.py
│   └── predict.py
│── app/
│   └── interface.py
│── README.md
│── requirements.txt
│── results/

📊 Literature Survey (Summary)

Season Classification using CNN on leaf images
Supports plant-based visual prediction methods.

Environmental data–based season detection
Shows that parameters like temperature and rainfall significantly affect seasonal changes.

Phenology detection using Computer Vision
Confirms the link between plant biological stages and seasons.

Deep learning for weather and seasonal pattern prediction
Proves deep learning outperforms traditional ML.

(References available in PPT) 

zerothreview_team_B2_ppt

📈 Results

Hybrid model significantly outperforms image-only or climate-only models.

Accurate seasonal prediction achieved through multimodal fusion.

🔧 Tech Stack

Python

TensorFlow / PyTorch

OpenCV

NumPy / pandas

Flask / Streamlit (for UI)

▶️ How to Run
pip install -r requirements.txt
python src/predict.py


Or run the interface:

python app/interface.py

🧪 Sample Input

Plant/tree image (JPEG/PNG)

Environmental values:

temp = 28°C

humidity = 62%

soil moisture = 40%

wind = 3.4 m/s

cloud visibility = 60%

📤 Output Example
Predicted Season: Summer
Confidence: 92.4%

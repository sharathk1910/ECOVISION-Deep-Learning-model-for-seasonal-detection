ECOVISION: Deep Learning Model for Seasonal Detection
Batch: B-02 | Department of Computer Science & Engineering
Srinivasa Ramanujan Institute of Technology, Ananthapuramu
📌 Project Overview

ECOVISION is an AI-powered deep learning system designed to detect the current season using a combination of:

Plant/Tree Image (Phenology)

Environmental Parameters such as
Temperature, Humidity, Precipitation, Pressure, Wind Speed, Soil Moisture, Solar Radiation, Cloud Visibility.

The system uses CNN-based image analysis along with machine learning models for environmental data to provide accurate and reliable season prediction.

🎯 Objectives
Primary Objective

To develop a multimodal deep learning model that predicts the season by analyzing both plant images and climatic parameters.

Supporting Objectives

To assist biotechnology and plant science research with accurate phenological season detection.

To support environmental monitoring and ecological studies.

To help students and researchers understand seasonal patterns through an AI-powered system.

To achieve higher accuracy compared to traditional image-only or climate-only methods.

🧩 Problem Statement

Traditional seasonal identification methods depend on:
✔ Manual plant observation
✔ Isolated weather reports

These approaches often lead to human error, subjectivity, and inconsistent results.
Existing research either:

Uses only plant images, ignoring weather conditions, or

Uses only weather parameters, ignoring biological changes in plants.

There is no unified system that combines both.

ECOVISION solves this by integrating plant phenology + climatic data to produce a highly accurate season classifier.

📚 Literature Survey (Summary)

Key research that supports this project:

Singh et al., 2021 – CNN for plant leaf seasonal classification.

Zhou et al., 2021 – Machine learning using environmental factors for season detection.

Das & Sen, 2020 – Computer vision for studying plant phenology.

Rai & Kaur, 2022 – Deep learning models for environmental and seasonal pattern prediction.

These studies justify the need for a multimodal AI system like ECOVISION.

🔧 Proposed System Architecture
1. Image Processing Module (CNN)

Extracts features such as leaf

Color

Texture

Dryness

Flowering/Fruiting patterns

2. Environmental Data Module

Processes parameters:

Temperature

Humidity

Wind speed

Precipitation

Pressure

Soil Moisture

Cloud Visibility

3. Feature Fusion Layer

Combines image-based features + environmental data to strengthen prediction accuracy.

4. Prediction Output

Displays the predicted season

Provides a confidence score

User-friendly interface for uploading image + inputting parameters

🏗️ Tech Stack

Python

TensorFlow / Keras (CNN Model)

Scikit-learn (Machine Learning)

Flask / Streamlit (Frontend UI)

NumPy, Pandas, Matplotlib

📂 Project Structure (Suggested)
ECOVISION/
│── dataset/
│── models/
│── src/
│   ├── cnn_model.py
│   ├── data_processing.py
│   ├── fusion_model.py
│   ├── predict.py
│── app/
│   ├── ui.py
│── results/
│── README.md
│── requirements.txt

📈 Applications

Agriculture planning

Ecological and biodiversity research

Seasonal phenology studies

Weather-based research

Education and academic projects

📖 References

(As per PPT)

Singh K. S. & Gupta R., Season Classification Using Plant Leaf Images and CNN Models, 2021

Zhou M., Li Y., Chen X., Environmental Feature-Based Season Detection, IEEE, 2021

Das A., Sen N., Plant Phenology Detection Using Computer Vision, 2020

Rai P., Kaur S., Deep Learning for Seasonal Pattern Prediction, 2022

🔗 GitHub Dashboard Link

Repository: https://github.com/Sharath599/Batch-B02-2025-2026

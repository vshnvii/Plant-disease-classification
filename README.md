# Plant Disease Classification

A deep learning-based web app that classifies **plant leaf diseases** using **MobileNetV2** and **TensorFlow**, served through a **Streamlit** frontend.  
Supports multiple plant types including potatoes, tomatoes, bell peppers, and more.

## Features

-  **Transfer Learning** with MobileNetV2
-  **Image Upload** and disease classification
-  ~94% validation accuracy on **PlantVillage** dataset
-  **Streamlit Web App** for easy local deployment
-  Detects multiple disease types (Early Blight, Late Blight, Healthy, etc.)

## Model Details

- **Architecture:** MobileNetV2
- **Training Dataset:** [PlantVillage](https://www.kaggle.com/datasets/emmarex/plantdisease)

## Youtube Demo
- Watch the project in action on YouTube:
- https://youtu.be/LGbEws6xSSY

## How to Run Locally
# 1. Clone the repo
- git clone https://github.com/vshnvii/Plant-disease-classification.git
- cd Plant-disease-classification
# 2. Streamlit
- streamlit run app.py

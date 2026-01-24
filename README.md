# AI Image Classifier

An AI-powered **Image Classification web application** built using **Streamlit** and **TensorFlow’s MobileNetV2** model.  
Users can upload an image, and the application predicts the **top three image classes** along with confidence scores using a pre-trained deep learning model.

---

## Project Overview

This project showcases the integration of a pre-trained deep learning model into an interactive web application.
An uploaded image is processed and passed through the MobileNetV2 model, which outputs prediction probabilities. 
The application displays the three most probable classes, making the results easy to interpret.

---

## Features

- Image classification using a pre-trained MobileNetV2 model
- Displays top three predicted classes with confidence scores
- Simple and responsive user interface built with Streamlit
- Lightweight and efficient inference suitable for local execution

---

## Model Used

### MobileNetV2

MobileNetV2 is a lightweight convolutional neural network designed for efficiency and speed. 
It is pre-trained on the ImageNet dataset containing 1,000 object categories, making it suitable for general-purpose image classification tasks.

---

## Tech Stack & Libraries

- **TensorFlow** – Model loading and inference
- **Streamlit** – Web application interface
- **OpenCV (opencv-python)** – Image preprocessing
- **Pillow (PIL)** – Image handling
- **NumPy** – Numerical operations

---

## Installation & Setup

```bash
git clone https://github.com/AmarShaik/AI-Image-Classifier.git

cd AI-Image-Classifier

python3 -m venv .venv

source .venv/bin/activate

python -m pip install --upgrade pip

pip install tensorflow streamlit opencv-python pillow numpy

streamlit run main.py

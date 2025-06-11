# AI Image Classifier

This is a simple AI Image Classifier web app built using **Streamlit** and **TensorFlow's MobileNetV2** model. Upload an image, and the app will use a pre-trained deep learning model to predict the top 3 classes of the image.

---

## Features

- Uses MobileNetV2 pretrained on ImageNet dataset for classification.  
- Simple, clean UI using Streamlit.  
- Shows top 3 predicted labels with confidence scores.  
- Runs locally on your machine.

---

## About the Project and Libraries

- **TensorFlow:** A powerful open-source machine learning framework by Google. Provides the MobileNetV2 model used here to classify images. TensorFlow handles the deep learning computations under the hood.  
- **OpenCV (opencv-python):** A popular computer vision library used to preprocess images (resize, convert) before feeding them to the model.  
- **Streamlit:** A Python library for creating interactive web apps with minimal code. It powers the user interface, file uploader, buttons, and displays output in a browser.  
- **Pillow (PIL):** Used for opening and handling image files inside the app.  
- **NumPy:** Essential for numerical operations on image data arrays, helping prepare images for model input.

---

## Prerequisites

- Python 3.11 (compatible with this project)  
- Basic familiarity with terminal / command prompt  
- Internet connection to download model weights on first run  

---

## Installation & Setup

1. Clone this repository or download the source code and extract it.  
2. Open your terminal or PowerShell in the project folder.

3. Create and activate a virtual environment (recommended) to isolate dependencies:

On Windows (PowerShell):

python -m venv .venv  
.\.venv\Scripts\Activate.ps1  

On macOS/Linux (bash):

python3 -m venv .venv  
source .venv/bin/activate  

4. Upgrade pip and install required packages including TensorFlow and Streamlit:

python -m pip install --upgrade pip  
pip install tensorflow streamlit opencv-python pillow numpy  

> **Note:**  
> TensorFlow is **not** included in `pyproject.toml` dependencies, so you must install it manually as shown above.

---

## Running the App

Run the Streamlit app locally by executing:

streamlit run main.py  

This will start a local server, usually accessible at:

http://localhost:8501  

Open this URL in your web browser to interact with the app.

---

## Usage

- Upload images in JPG, PNG, or JPEG format.  
- Click the **Classify Image** button.  
- View the top 3 predicted classes with confidence scores.

---

## Troubleshooting

- If you encounter missing module errors, ensure your virtual environment is activated and all dependencies are installed properly.    
- Use Python 3.11 to avoid compatibility issues.  
- If image upload or classification fails, check image format and try again.

---
gments

- [TensorFlow](https://www.tensorflow.org/)  
- [Streamlit](https://streamlit.io/)  
- MobileNetV2 pretrained model on ImageNet dataset

---

Feel free to reach out if you have questions or need help running the app!

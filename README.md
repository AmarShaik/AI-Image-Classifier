# AI Image Classifier

This is a simple AI Image Classifier web app built using **Streamlit** and **TensorFlow's MobileNetV2** model. Upload an image, and the app will use a pre-trained deep learning model to predict the top 3 classes of the image.

---

## Features

- Uses MobileNetV2 pretrained on ImageNet dataset for classification.
- Simple, clean UI using Streamlit.
- Shows top 3 predicted labels with confidence scores.
- Runs locally on your machine.

---

## Prerequisites

- Python 3.11 (compatible with this project)
- Basic familiarity with terminal / command prompt
- Internet connection to download model weights on first run

---

## Installation & Setup

Clone this repository or download the source code and extract it. Open your terminal or PowerShell in the project folder.

Create and activate a virtual environment (recommended) to isolate dependencies:

On Windows (PowerShell):

python -m venv .venv  
.\.venv\Scripts\Activate.ps1  

On macOS/Linux (bash):

python3 -m venv .venv  
source .venv/bin/activate  

Upgrade pip and install required packages including TensorFlow and Streamlit:

python -m pip install --upgrade pip  
pip install tensorflow streamlit opencv-python pillow  

Note: TensorFlow is **not** included in `pyproject.toml` dependencies, so install it manually as above.

---

## Running the App

Run the Streamlit app locally by executing:

streamlit run main.py  

This will start a local server, usually accessible at `http://localhost:8501` in your browser. Use the interface to upload images and get classification predictions.

---

## Usage

- Upload images in JPG, PNG, or JPEG format.
- Click the **Classify Image** button.
- View the top 3 predicted classes with confidence scores.

---

## Troubleshooting

- If you encounter missing module errors, ensure your virtual environment is activated and all dependencies are installed.
- TensorFlow installation requires a stable internet connection and may take some time.
- Use Python 3.11 to avoid compatibility issues.

---

## License

This project is open source and free to use.

---

## Acknowledgments

- [TensorFlow](https://www.tensorflow.org/)  
- [Streamlit](https://streamlit.io/)  
- MobileNetV2 pretrained model on ImageNet dataset

---

Feel free to reach out if you have questions or need help running the app!

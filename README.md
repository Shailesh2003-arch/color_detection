This project implements a color detection model using Streamlit, identifying dominant colors in uploaded images.

Features
Detects dominant colors in images.
Provides color names, hexadecimal codes, and percentages.
Uses K-means clustering and a pre-trained MobileNetV2 model for preprocessing.
Usage
Install required packages.
Run with streamlit run app.py.
Upload an image, click "Detect Color".
Detected colors are displayed with details.
Model
Image preprocessing: Resize, normalize.
Feature extraction: MobileNetV2.
Color clustering: K-means.
Color name resolution: Webcolors.
Acknowledgments
MobileNetV2 pre-trained model.
Webcolors for color name resolution.

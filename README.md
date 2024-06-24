# License_Plate_Recognition_System

## Overview

This project is an Automatic License Plate Recognition (ALPR) application built using YOLO for object detection and EasyOCR for text recognition. The application allows users to upload images or videos, detects license plates, and extracts the text from them.

## Features

- **License Plate Detection**: Uses a trained YOLO model to detect license plates in images and videos.
- **Text Recognition**: Uses EasyOCR to recognize and display text from the detected license plates.
- **Streamlit Interface**: Provides a user-friendly web interface for uploading and processing files.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Required Python packages:
  - Streamlit
  - OpenCV
  - NumPy
  - PIL
  - EasyOCR
  - Matplotlib
  - Ultralytics (for YOLO)

### Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/license-plate-recognition.git
    cd license-plate-recognition
    ```

2. **Install the required packages**:
    ```sh
    pip install streamlit opencv-python-headless numpy pillow easyocr matplotlib ultralytics
    ```

3. **Download the trained YOLO model**:
    Place your trained YOLO model (e.g., `best_license_plate_model.pt`) in the appropriate directory. Update the path in the Streamlit app code if necessary.

### Usage

1. **Run the Streamlit app**:
    ```sh
    streamlit run app.py
    ```

2. **Upload an image or video**:
   - Navigate to the local URL provided by Streamlit.
   - Upload your image or video file through the interface.
   - The app will process the file, detect license plates, and display the results.




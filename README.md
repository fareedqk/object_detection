# YOLOv8 Object Detection and Segmentation with Streamlit

This project implements a dynamic object detection and segmentation tool using YOLOv8 models, where you can either **detect** or **segment** objects in **images**, **videos**, or through **live webcam feeds** using the Streamlit framework.

## Features

- **Dynamic Model Selection**: Choose between object detection or segmentation using YOLOv8 models.
- **Input Flexibility**: Supports:
  - **Images**
  - **Videos**
  - **Live webcam stream**
- **Real-time Processing**: Process your inputs and display results directly on Streamlit.
- **Customizable Output**: View either bounding boxes (for detection) or segmentations (for segmentation tasks).

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/yolov8-streamlit.git
    cd yolov8-streamlit
    ```

2. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv yolov8-env
    source yolov8-env/bin/activate  # On Windows: yolov8-env\Scripts\activate
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Make sure you have Streamlit and YOLOv8 installed:

    ```bash
    pip install streamlit ultralytics opencv-python-headless
    ```

## How to Run

To run the app, simply execute the following command in your terminal:

```bash
streamlit run app.py

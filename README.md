# Pathole Detection

## Description

This project focuses on detecting potholes from road images or video frames using machine learning. It preprocesses the input, runs predictions through a trained model, and highlights potholes with bounding boxes for easy visualization. The notebook is built to be simple, crisp, and easy to follow for experimentation or demos.

## Features

* Preprocess road images and video frames
* Detect potholes using ML model
* Display bounding boxes around detected potholes
* Export annotated results

## Requirements

* Python 3.8+
* jupyter / jupyterlab
* numpy, pandas, matplotlib, pillow, opencv-python
* torch or tensorflow (depending on model used)

## Installation

```bash
python -m venv venv
source venv/bin/activate   # or .\venv\Scripts\activate on Windows
pip install -r requirements.txt
```

## Usage

1. Open the notebook:

   ```bash
   jupyter notebook pathole_detection.ipynb
   ```
2. Run cells in order
3. Replace `input_image.jpg` or `input_video.mp4` with your own files to test detection

## Results

* Annotated images/videos with pothole bounding boxes
* Simple output reports in `outputs/`

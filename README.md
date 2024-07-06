# Robust Human Detection, Tracking, and Counting

![Python](https://img.shields.io/badge/Language-Python-blue)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## About

This repository contains a robust system for human detection, tracking, and counting using YOLOv8 and other advanced techniques. The project integrates several key features to enhance accuracy and reliability in various environments.

## Features

- **Human Detection**: Utilizes the YOLOv8 model for accurate human detection.
- **Object Tracking**: Tracks detected humans over video sequences.
- **Counting**: Counts the number of humans detected in each frame.

## Files

- `main.py`: Main script for running detection, tracking, and counting.
- `tracker.py`: Script specifically for tracking detected objects.
- `coco.txt`: List of objects from the COCO dataset.
- `download.txt`: Additional resources and download links.
- `yolov8s.pt`: Pre-trained YOLOv8 model weights.
- `video.mp3` and `p3.mp3`: Input video files for detection, tracking, and counting.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/amanmaner011/Robust-Human-Detection-Tracking-Counting.git
2. Navigate to the project directory:
   ```bash
   cd Robust-Human-Detection-Tracking-Counting/src
3. Install the required dependencies:
   ```bash
   pip install cv2 pandas numpy ultralytics cvzone

## Usage

### Running the Tracking and Detection
1. Execute the tracking script:
   ```bash
   python tracker.py
2. Execute the main script:
   ```bash
   python main.py

### Customizing the Tracking Behavior
- Modify `tracker.py` to adjust tracking parameters and improve performance based on your specific use case.

### Object List
- The `coco.txt` file contains a list of objects from the COCO dataset that the tracker.py script can monitor.

### Acknowledgements
- The **YOLOv8** model and its contributors.
- The **COCO** dataset for providing a comprehensive list of objects.

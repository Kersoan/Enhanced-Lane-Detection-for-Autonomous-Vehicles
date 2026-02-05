# Enhanced Lane Detection for Autonomous Vehicles

## Overview
This project implements an enhanced lane detection pipeline designed for autonomous driving systems.  
It focuses on robust lane identification using computer vision techniques under varying road conditions.

---

## Key Features
- Image preprocessing (grayscale, blurring, edge detection)
- Lane detection using classical CV techniques 
- Lane visualization and overlay
- Modular and configurable pipeline

---

## Tech Stack
- Python
- OpenCV
- NumPy
- Matplotlib

---

## Project Structure:
```
Enhanced-Lane-Detection-for-Autonomous-Vehicles/
│
├── notebooks/
│   └── LaneDetection.ipynb        # Original experimentation notebook
│
├── src/
│   ├── __init__.py
│   ├── preprocessing.py          # Image preprocessing (blur, grayscale, edges)
│   ├── lane_detection.py          # Lane detection logic (Hough, contours, etc.)
│   ├── visualization.py           # Drawing lanes, overlays
│   └── utils.py                   # Helper functions
│
├── data/
│   ├── images/
│   │   ├── raw/
│   │   └── processed/ 
│   └── videos/                    # Optional (dashcam videos)
│
├── assets/
│   ├── output_examples.png        # Lane detection results
│   └── pipeline.png               # Processing pipeline diagram
│
├── configs/
│   └── config.yaml                # Thresholds, parameters (from your config file)
│
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE

# Ghost-Free Object Tracking with YOLO & Kalman Filter

This project implements an **advanced object tracking pipeline** using YOLO for object detection and a **Kalman filter–based tracker with ghost track prevention**. It processes videos, assigns unique IDs to objects, filters out unreliable tracks, visualizes results, and saves both annotated videos and CSV tracking data.

---

## Features

- Detect and track objects in video using YOLO.
- Robust **Kalman filter tracking** with ghost track prevention.
- Advanced matching using **IoU and distance metrics**.
- Filters out unreliable or low-confidence tracks.
- Generates annotated video and CSV file with tracking info.
- Real-time FPS overlay and tracking status on video frames.

---

## Demo

<img src="output.gif" alt="Tracking Demo" style="width:70%; height:auto;">

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/merkut06/Object_Detection_Tracking_Yolo_Kalman.git
cd Object_Detection_Tracking_Yolo_Kalman

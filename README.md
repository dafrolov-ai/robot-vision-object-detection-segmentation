# Robot Vision: Object Detection and Segmentation

This repository contains a practical computer vision project focused on perception tasks for mobile robots and delivery robots.

The notebook demonstrates how modern deep learning models can be used to detect and segment urban objects that are relevant for robot navigation and safety.

---

## Project Goal

The goal of this project is to build a vision pipeline for a robot operating in an urban environment.

The robot must:
- detect dynamic and static obstacles,
- distinguish between allowed and forbidden areas,
- understand the scene structure using object detection and segmentation.

---

## Key Tasks

- Object Detection (OD) using YOLOv8
- Semantic and prompt-based segmentation using LangSAM
- Video-based inference for robotic perception
- Analysis of safe and unsafe objects for navigation

---

## Objects of Interest

### Forbidden objects (robot should avoid):
- people
- cars
- buses
- potholes
- trash bins
- bus stops
- other urban obstacles

### Allowed objects (robot can move through):
- sidewalks
- pedestrian crossings

---

## Technologies Used

- Python
- PyTorch
- YOLOv8 (Ultralytics)
- LangSAM (Language-driven Segment Anything)
- OpenCV
- NumPy
- Matplotlib
- MoviePy

All experiments are designed to run in Google Colab.

---

## Notebook Structure

1. Environment setup and library installation  
2. Utility functions for video loading and visualization  
3. Object detection with YOLOv8 on video streams  
4. Prompt-based image segmentation with LangSAM  
5. Analysis of detected and segmented objects  
6. Discussion of robotic perception logic  

---

## Practical Value

This project demonstrates how computer vision can be applied to real robotic systems:
- delivery robots,
- autonomous platforms,
- mobile inspection systems.

The pipeline can be extended with:
- trajectory planning,
- collision avoidance,
- multi-camera perception.

---

## 📓 Notebook

This repository contains a Jupyter notebook with extensive visual outputs
(images, GIFs, and video-based results).

Due to GitHub rendering limitations with interactive widgets, two versions are provided:

- **`robot_vision_od_and_segmentation_yolov8_langsam.clean.ipynb`**  
  Clean notebook version for correct rendering on GitHub (code + markdown).

- **`robot_vision_od_and_segmentation_yolov8_langsam.clean.html`**  
  Full visual report with all plots, images, and animations.

➡️ **Recommended:** open the `.html` file for the complete visual demonstration.

---

## Author

Prepared as part of an educational and applied computer vision webinar on robotic perception.

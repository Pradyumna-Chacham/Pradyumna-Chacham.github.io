---
title: "Real-Time Object Tracking with YOLOv9 & DeepSORT"
date: 2024-06-30
summary: "Developed a high-precision, real-time object tracking system for video streams using state-of-the-art computer vision models during my internship at Osmania University."
tags: ["Computer Vision", "Deep Learning", "Python", "YOLOv9", "DeepSORT"]

image:
  caption: 'Replace this with an image of your project'
  focal_point: 'Smart'
---

During my internship at Osmania University, I built a complete, real-time object tracking system with practical applications in real-world scenarios.

The system uses a two-stage approach:
1.  **Detection**: The state-of-the-art YOLOv9 model is used to detect objects in each video frame with high accuracy.
2.  **Tracking**: The DeepSORT algorithm takes the detections and assigns a unique ID to each object, tracking its movement across subsequent frames.

The final implementation successfully tracked over 500 objects across various video feeds, achieving a 73% IDF1 score and 92.5% ID Precision, demonstrating its reliability and effectiveness.
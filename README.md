BiFPN-YOLOv8: Traffic Light Detection

This repository contains an enhanced YOLOv8n model integrated with BiFPN and four detection heads, optimized for traffic light detection. The model is trained and evaluated on the LISA dataset, supporting six traffic light classes:

'go', 'stop', 'stopLeft', 'warning', 'goLeft', and 'warningLeft'.

🔹 Features
✅ BiFPN Neck – Improves multi-scale feature fusion for better small object detection.
✅ Four Detection Heads – Enhances detection of small and distant traffic lights.
✅ Anchor-Free Prediction – Simplifies object localization for increased accuracy.
✅ Optimized with AdamW – Improves training stability and convergence.
✅ Real-Time Performance – Designed for autonomous driving and smart traffic systems.

![Copy of yolov8n drawio](https://github.com/user-attachments/assets/07e16bda-d046-4dfe-8654-ab6696fc3b47)



📂 Dataset
Dataset Used: LISA Traffic Light Dataset
Resolution: 1280 × 960 pixels
Number of Images: 14,034 (daylight images)
https://www.kaggle.com/datasets/mbornoe/lisa-traffic-light-dataset

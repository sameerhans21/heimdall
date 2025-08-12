# 🚬 Smoke Detection in Videos using YOLOv8

This project implements a smoke detection pipeline using **Ultralytics YOLOv8**.  
It processes video streams frame-by-frame, detects smoke, and outputs annotated videos with bounding boxes, labels, and confidence scores.

---

## 📌 Features
- Load videos (`.mp4` or equivalent) for analysis
- Frame-by-frame object detection with YOLOv8
- Annotated video output with bounding boxes & confidence
- Adjustable detection confidence threshold
- Works on single videos or entire folders
- Easy to adapt for real-time camera streams

---

## 🛠 Requirements
Install the dependencies using:
```bash
pip install -r requirements.txt

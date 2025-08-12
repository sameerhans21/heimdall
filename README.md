# Training Datasets

For all the datasets in training, I have all the violent videos in **Fight** folder and normal or non-violeent videos in **NonFight** folder 

---

## Features
- Load videos (`.mp4` or equivalent) for analysis
- Frame-by-frame object detection with YOLOv8
- Annotated video output with bounding boxes & confidence
- Adjustable detection confidence threshold
- Works on single videos or entire folders
- Easy to adapt for real-time camera streams

---
best_vmae_chat_ucf3.pth --> This model can be used to detect violence directly, i explained in the scirpt how to use it directly.

TRAINED ON RWF-2000/train, hockeyFight, surveillance-camera-fight, RealLifeViolenceDataset, chatalet_2_train, movies, ucf(fight,assault))
---
 
## 🛠 Requirements
Install the dependencies using:
```bash
pip install -r requirements.txt

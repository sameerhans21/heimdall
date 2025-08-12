## Pretrained model
I use a VideoMAE model trained on Kinetics dataset **MCG-NJU/videomae-base-finetuned-kinetics**

---

## Training Datasets

For all the datasets in training, I have all the violent videos in **Fight** folder and normal or non-violeent videos in **NonFight** folder 

---

## Chatalet Dataset
- we have 40 videos, i divide them into clips of 16 frames (as they are labeled frame-wise)
- For a particular video, after getting the frames of a video, clip 1 is frame 1-16, clip 2 is frame 17-32 ........
- i consider these labels (Fight, Pushing, Running, Handling) as **Fight** and rest as **NonFight**
- Determine the majority label of the frames inside the clip (if >50% of frames in the clip are violent, label the clip as violent)  
- Use the clip as input to the VideoMAE model
- Compare prediction to majority label


---
## best_vmae_chat_ucf3.pth
- This model can be used to detect violence directly, i explained in the script how to use it directly.
- TRAINED ON **RWF-2000/train, hockeyFight, surveillance-camera-fight, RealLifeViolenceDataset, chatalet_2_train, movies, ucf(fight,assault))**

---
 
## 🛠 Requirements
Install the dependencies using:
```bash
pip install -r requirements.txt

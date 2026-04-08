# 🚦 Smart Traffic Light Controller — YOLOv3 + Python

Real-time vehicle detection and adaptive traffic signal system 
that reduced simulated vehicle wait time by **40%** using 
computer vision.

## 🎯 What it does
- Detects vehicles in real-time using YOLOv3
- Counts vehicles per lane
- Dynamically adjusts signal timing based on lane density
- Achieved 40% reduction in average vehicle wait time


## 📸
![WhatsApp Image 2026-04-08 at 2 53 43 PM (1)](https://github.com/user-attachments/assets/4ab9f79d-73bb-4276-8b8f-ae5b4f099971)
[WhatsApp Image 2026-04-08 at 2 53 43 PM](https://github.com/user-attachments/assets/bcc81b4a-3f73-4e4d-86f7-87b33b6b7caa)
ents/assets/3d36d295-9432-4826-ba1f-db9075a60616)

![WhatsApp Image 2026-04-08 at 2 53 43 PM (3)](https://github.com/user-attachments/assets/33f29c13-e7c2-493b-9871-84d56d2570e2)


## 🛠 Tech Stack
- Python, YOLOv3, OpenCV

## 🚀 How to Run

Clone the repository
```bash

git clone https://github.com/keertiG-1296/Traffic-Controller.git
cd Traffic-Controller
```

Install dependencies
```bash
pip install -r requirements.txt
```
Ensure YOLO weights are present
```bash
git lfs install
git lfs pull
```

Run the code
```bash
python 2lane.py
```


## 📊 Results
| Metric | Value |
|--------|-------|
| Vehicle detection accuracy | ~85% |
| Wait time reduction | 40% |


## 💡 What I learned
- Custom YOLO inference pipelines
- Real-time image preprocessing
- Signal optimization logic




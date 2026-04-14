# 🚦 Smart Traffic Light Controller

Real-time vehicle detection and adaptive traffic signal system using YOLOv3 
and OpenCV — reduced simulated vehicle wait time by 40% through 
density-based signal timing.

---

## 📊 Results

| Metric | Value |
|--------|-------|
| Vehicle Detection Accuracy | ~85% |
| Wait Time Reduction | 40% |
| Detection Model | YOLOv3 (pre-trained) |
| Lanes Supported | 2-lane intersection |

---

## 🎯 How It Works

1. **Vehicle Detection** — YOLOv3 runs inference on each lane feed in real-time using OpenCV
2. **Density Scoring** — Vehicle count per lane is computed from detection outputs
3. **Adaptive Timing** — Signal duration is dynamically adjusted proportional to lane density scores
4. **Result** — Denser lanes get longer green windows, reducing overall wait time by 40% in simulation

---

## 📸 Demo

![WhatsApp Image 2026-04-08 at 2 53 43 PM (1)](https://github.com/user-attachments/assets/4ab9f79d-73bb-4276-8b8f-ae5b4f099971)
[WhatsApp Image 2026-04-08 at 2 53 43 PM](https://github.com/user-attachments/assets/bcc81b4a-3f73-4e4d-86f7-87b33b6b7caa)
ents/assets/3d36d295-9432-4826-ba1f-db9075a60616)

![WhatsApp Image 2026-04-08 at 2 53 43 PM (3)](https://github.com/user-attachments/assets/33f29c13-e7c2-493b-9871-84d56d2570e2)

---

## 🛠 Tech Stack

- **Detection:** YOLOv3 (pre-trained COCO weights) + OpenCV
- **Logic:** Python — custom density scoring and signal timing algorithm
- **Weights:** Stored via Git LFS

---

## 🚀 Getting Started

**1. Clone the repo**
```bash
git clone https://github.com/keertiG-1296/Traffic-Controller.git
cd Traffic-Controller
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Pull YOLO weights**
```bash
git lfs install
git lfs pull
```

**4. Run**
```bash
python 2lane.py
```

---

## 📁 Dataset / Input

Tested on simulated traffic video feeds. YOLOv3 weights pre-trained 
on COCO dataset — no custom training required for vehicle detection.





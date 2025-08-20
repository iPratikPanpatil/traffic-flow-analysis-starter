# 🚦 Traffic Flow Analysis Starter

This project analyzes traffic flow from video input using computer vision.  
It detects vehicles, counts them, and generates useful insights with annotated outputs.

---
### Project Structure
├─ traffic-flow-analysis-starter
│ ├─.gitignore
├ ├─ requirements.txt
├─ traffic_flow.py
├─ yolo8n.pt
├─ Video1.mp4 # input video
│ └─ lanes.json # lane calibration data
├─ outputs/
│ ├─ annotated.mp4 # processed video with vehicle tracking
│ ├─ counts.csv # vehicle counts exported to Excel
├─ screenshots/ # vehicle counts screenshots
└─ README.md
---
## 🎥 Demo Video

- [Watch on Google Drive](https://drive.google.com/file/d/1YW3uhd7axu5TIvib5niqjqgFOSPsJE4s/view?usp=sharing)  
- [Download from GitHub](Captured.mp4)

---

## 📸 Screenshots

### Vehicle Count Results

| Screenshot 1 | Screenshot 2 |
|--------------|--------------|
| ![Counts Screenshot 1](image1.png) | ![Counts Screenshot 2](image2.png) |

| Screenshot 3 | Screenshot 4 |
|--------------|--------------|
| ![Counts Screenshot 3](image3.png) | ![Counts Screenshot 4](image4.png) |

---

## ✨ Features
- Detects and tracks vehicles from traffic videos  
- Counts number of vehicles per lane  
- Generates annotated output video  
- Exports vehicle counts to CSV for analysis  

---

## 🛠 Tech Stack
- Python  
- OpenCV  
- NumPy  
- Pandas  

---

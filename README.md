# 🚦 Traffic Flow Analysis Starter

This project analyzes traffic flow from video input using computer vision.  
It detects vehicles, counts them, and generates useful insights with annotated outputs.

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

### Technical Summary Approach

Implemented a traffic flow analysis system that processes video input to detect, track, and count vehicles.
Used computer vision techniques to identify moving vehicles and track them across frames.
Lane calibration (lanes.json) ensures vehicles are counted correctly per lane.

### Outputs include:

Annotated video with bounding boxes and vehicle IDs.
CSV file containing vehicle counts for further analysis.
Screenshots highlighting detected counts for validation.

### Challenges

Lane detection accuracy: Initial calibration caused miscounts when vehicles overlapped.
Multiple vehicle occlusions: Vehicles blocking each other made tracking inconsistent.
Performance optimization: Processing high-resolution video frames caused slow execution.

### Solutions

Applied lane calibration data (lanes.json) to define valid regions for counting.
Used tracking algorithms to maintain consistent vehicle IDs even during partial occlusions.
Optimized frame processing by resizing input and applying selective region analysis, which improved speed without major accuracy loss.

---

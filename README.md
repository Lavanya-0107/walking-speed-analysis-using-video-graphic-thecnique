# Walking Speed Analysis Using Video Graphic Technique

## 📌 Project Description

This project analyzes the walking speed of multiple people from CCTV or recorded video.

The system uses YOLOv8 for person detection and ByteTrack for tracking people across video frames. Pixel-to-distance calibration is used to calculate the walking speed of each person.

## 🎯 Objectives

- Detect people from video.
- Track multiple people continuously.
- Calculate the walking speed of each person.
- Analyze pedestrian trajectories.
- Count people crossing a specific region.
- Calculate polygon areas.
- Store the analysis results in CSV files.

## 🛠️ Technologies Used

- Python
- OpenCV
- YOLOv8
- ByteTrack
- NumPy
- Pandas
- Matplotlib
- CSV

## ⚙️ Main Features

1. Person detection using YOLOv8.
2. Multi-person tracking using ByteTrack.
3. Walking speed calculation.
4. Person trajectory visualization.
5. Crossing count analysis.
6. Polygon area calculation.
7. CSV-based result generation.

## 📂 Project Files

| File | Description |
|---|---|
| `main22 (2).py` | Main Python program |
| `person_trajectories.png` | Person trajectory visualization |
| `enhanced_count_data.csv` | Count analysis data |
| `enhanced_crossing_counts.csv` | Crossing count results |
| `enhanced_polygon_areas.csv` | Polygon area results |
| `trajectories_data_enhanced.csv` | Trajectory data |
| `yolov8s.pt` | YOLOv8 model |

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Lavanya-0107/walking-speed-analysis-using-video-graphic-thecnique.git
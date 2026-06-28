# Player Tracking in Sports Videos with YOLO

# DS5216 - Player Tracking in Sports Videos

## Overview
Computer vision system to detect and track players in sports videos using YOLOv8.

## Dataset
5 sports video clips (5-10 seconds each)
📁 [Download Videos](https://drive.google.com/drive/folders/1BI5AbjRQ3o8N1lat_ivlz59O1jV1YlPV?usp=sharing)

Sports covered: Cricket, Football, Rugby, Basketball, Tennis

## Models Used
- **Detection**: YOLOv8 Nano (yolov8n.pt) - COCO pre-trained
- **Tracking**: ByteTrack (built into Ultralytics)
- **Keypoints**: YOLOv8 Pose (yolov8n-pose.pt) [Bonus]

## How to Run
1. Open `PlayerTrackingwithYOLO_SupunDTS.ipynb` in Google Colab
2. Enable GPU: Runtime → Change runtime type → T4 GPU
3. Run all cells in order

## Results
See `screenshots/` folder for detection and tracking outputs.

## Files
- `PlayerTrackingwithYOLO_SupunDTS.ipynb` - Main notebook
- `screenshots/` - Detection, tracking, and keypoint screenshots
- `Report_PA02_DTS2418_DS5216.pdf` - Full assignment report

## Requirements
ultralytics, opencv-python, torch, supervision, matplotlib

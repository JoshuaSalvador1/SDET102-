# SDET102-

# Smart People Counter Using YOLO

## Project Description
This project is a computer vision application that uses YOLO object detection and tracking to count people entering and exiting an area in a video. The system tracks people as they cross a virtual boundary line and calculates real-time occupancy.

## Features
- Person detection using YOLO
- Real-time object tracking
- Entry and exit counting
- Occupancy monitoring
- Video processing and output generation

## Tools and Libraries
- Python
- OpenCV
- Ultralytics YOLOv8
- Google Colab
- NumPy

## Input
The system accepts prerecorded videos or webcam footage containing people moving through a scene.

## Output
The output video displays:
- Bounding boxes around people
- Tracking IDs
- Counting line
- Entry and exit totals
- Current occupancy

## How to Run
1. Open the notebook in Google Colab
2. Install required libraries
3. Upload a test video
4. Run all notebook cells
5. Download the processed output video

## Limitations
- Accuracy may decrease in crowded scenes
- Fast movement may occasionally cause tracking errors
- Lighting conditions can affect detection performance

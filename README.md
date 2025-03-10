# Facial Recognition Attendance System

## Demo Video

Click the thumbnail below to watch the demo video on YouTube:

[![Watch the video](https://img.youtube.com/vi/Nw-wETbPsKo/0.jpg)](https://youtu.be/Nw-wETbPsKo)

## Project Overview
This project demonstrates how to perform **facial recognition** with high accuracy. We will first cover the theory and basic implementation before building a **real-time attendance system** that detects faces via a webcam and records attendance in an **Excel (CSV) file**.

## Project Steps
1. **Basic Facial Recognition** - Learn the core concepts and test face detection and recognition.
2. **Attendance System Implementation** - Use a webcam to detect faces and mark attendance in a CSV file.
3. **Live Attendance Recording** - The system updates the attendance sheet automatically when a recognized face is detected.

## Code Files
- **`Basic.py`** - A simple script to test face detection and encoding.
- **`AttendanceProject.py`** - The main script for real-time face detection and attendance tracking.
- **`Attendance.csv`** - The output file where attendance records are stored.

## Local Setup
### Installation
Ensure you have **Python 3.8+** installed and install the required dependencies:

```bash
pip install opencv-python numpy face-recognition
```

### Running the Project
#### 1. Basic Face Recognition Test
```bash
python Basic.py
```
#### 2. Live Attendance System
```bash
python AttendanceProject.py
```
This will activate the webcam and start detecting faces.

## Data
- The project requires images of individuals stored in the **`ImagesAttendance`** folder.
- Each image should be named after the person (e.g., `John_Doe.jpg`).
- The attendance records will be saved in `Attendance.csv`.

## Features
**Real-time face recognition** using OpenCV & `face_recognition` library  
**Live attendance marking** in a CSV file  
**High accuracy** with face encodings  
**Multiple faces detection** support  

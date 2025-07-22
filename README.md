# Face Recognition Attendance System

This is a Python-based Face Recognition Attendance System built using Flask, OpenCV, and machine learning (KNN). It allows users to register faces, train a model, and take attendance via webcam in real time.

## Features

- Register new users with face images via webcam
- Train a face recognition model using KNN
- Detect and identify faces using Haar Cascades
- Log attendance with name, roll number, and time
- Simple Flask web interface
- CSV-based attendance record generation

## Tech Stack

- Python
- Flask
- OpenCV
- Scikit-learn (KNN)
- Pandas, NumPy
- HTML/CSS Templates (via `render_template`)
- Haarcascade for face detection
- pywin32 (for speech synthesis on Windows)

<img width="947" height="479" alt="Capture" src="https://github.com/user-attachments/assets/f71153e4-9488-4b1a-9878-56e0d606b9c5" />
<img width="746" height="695" alt="background" src="https://github.com/user-attachments/assets/edc96a93-9834-4215-aa67-211402721b74" />
  

## Usage:

Open in browser at http://localhost:5000/

Use Add User to register a new face.

Click Start Attendance and press O when a face is recognized.

Attendance is saved in Attendance/Attendance-DD_MM_YY.csv.

## Notes

Ensure webcam access is enabled.

App uses Windows TTS API (SAPI.SpVoice)—only compatible with Windows OS.

Esc key exits camera feed.

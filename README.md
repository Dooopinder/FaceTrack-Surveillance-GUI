# FaceTrack-Surveillance-GUI

A real-time face recognition and gaze-tracking surveillance system with a Tkinter GUI. Built using OpenCV, dlib, and face_recognition, it detects known and unknown individuals, tracks gaze direction, and flags suspicious activity.

## 🔧 Features

- ✅ Save and register known faces via GUI
-  Real-time face detection and identification
-  Eye gaze tracking using facial landmarks (dlib)
- 🚨 Flags and pauses on 5 off-focus gaze violations
-  Saves session metadata and violation snapshots
-  Tkinter-based GUI for easy control and visualization
- 🗂️ Saves frame-by-frame recordings in session folders

## 🖥️ Interface

- **SAVE FACE** – Captures and registers a new known face.
- **START** – Begins surveillance session.
- **STOP** – Stops surveillance without closing the app.
- **RESUME** – Manually resumes after 5 gaze-off violations.
- **EXIT** – Safely closes the app and saves session data.

FOLDER STRUCTURES
facedetection/
├── known_faces/                  # saved known faces
│   └── JOHN.jpg
├── sessions/
│   └── 2025-05-12_1510/
│       ├── frame_00001.jpg
│       ├── unknown_151202.jpg
│       ├── gaze_violation_151310.jpg
│       └── metadata.json



##⚙️ Installation
Using pip:

pip install face_recognition dlib opencv-python numpy Pillow
Using conda:

conda install -c conda-forge face_recognition dlib opencv numpy pillow
Note: You must also download the facial landmarks model.



##📥 Required File
Place the following file in the same directory as your Python script:

shape_predictor_68_face_landmarks.dat

📎 Download:
https://github.com/davisking/dlib-models/raw/master/shape_predictor_68_face_landmarks.dat

##🚀 Usage
Run the application:

python main.py

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

# 🧊 3D HoloCube with Hand Gesture Control

This Python project renders a 3D holographic cube using OpenGL and lets you control it using real-time hand gestures (pinch and motion tracking) via MediaPipe and your webcam.

## 🎯 Features

- 3D cube rendering with transparent faces and glowing edges  
- Rotate the cube by moving your index finger  
- Zoom in/out with pinch gestures (thumb + index)  
- Real-time webcam hand tracking using MediaPipe  
- Intuitive interaction with just one hand

## 🛠️ Tech Stack

- Python 3.9+  
- OpenCV (`cv2`)  
- PyGame (for OpenGL context & rendering)  
- PyOpenGL (`OpenGL.GL`, `OpenGL.GLU`)  
- MediaPipe (hand tracking)  
- NumPy (required implicitly)

## 🚀 How to Run

1. 🔁 Clone the repo or download the `.py` file.  
2. 📦 Create a virtual environment (recommended):
    ```bash
    python -m venv holoenv
    holoenv\Scripts\activate  # Windows
    source holoenv/bin/activate  # Linux/macOS
    ```
3. ✅ Install dependencies:
    ```bash
    pip install numpy==2.2.0 opencv-python pygame PyOpenGL mediapipe
    ```
4. 🎥 Make sure your webcam is connected and not used elsewhere.  
5. ▶️ Run the script:
    ```bash
    python 3D_HoloCube.py
    ```

## 🧠 How it Works

- MediaPipe detects hand landmarks from webcam frames.  
- Pinch detection (distance between thumb and index finger) controls zoom.  
- Movement of the index finger controls cube rotation.  
- OpenGL handles 3D rendering with translucent faces and solid edges.

## 🙌 Credits

- Inspired by futuristic hand-controlled holographic UIs (like Iron Man).  
- Built with using Python and open-source libraries.

---

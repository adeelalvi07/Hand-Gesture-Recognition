# ✋ Hand Gesture Detection using MediaPipe

A real-time **Hand Gesture Detection** project using **Python, OpenCV, and MediaPipe Tasks API**. The system uses a webcam to detect hand landmarks and recognize common hand gestures.

## 🚀 Features

* Real-time hand detection using webcam
* Detects up to 2 hands
* Identifies Left and Right hands
* Detects 21 hand landmarks
* Recognizes the following gestures:

  * ✊ Fist
  * 🖐️ Open Palm
  * 👍 Thumbs Up
  * 👎 Thumbs Down
  * ✌️ Peace / Victory
  * ☝️ Pointing
  * 👌 OK Sign

## 🛠️ Technologies

* Python
* OpenCV
* MediaPipe Tasks API
* Jupyter Notebook

## 📁 Project Structure

```text
Hand-Gesture-Detection/
│
├── Hand_Gesture_Detection.ipynb
└── README.md
```

## 📦 Installation

Install the required libraries:

```bash
pip install mediapipe opencv-python
```

The MediaPipe hand landmark model is automatically downloaded when the notebook is run for the first time.

## ▶️ How to Run

1. Clone or download this repository.
2. Open `Hand_Gesture_Detection.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
3. Install the required libraries.
4. Run all cells.
5. Allow webcam access when prompted.
6. Perform the supported gestures in front of the camera.

Press **Q** to close the webcam window.

## 🧠 How It Works

The system:

```text
Webcam
   ↓
OpenCV
   ↓
MediaPipe Hand Landmarker
   ↓
21 Hand Landmarks
   ↓
Finger Detection
   ↓
Gesture Classification
   ↓
Detected Gesture
```

Gesture classification is performed using the positions and distances between hand landmarks.

## 📌 Notes

* Good lighting improves detection accuracy.
* Keep your hand clearly visible to the camera.
* Gesture detection is rule-based and may not recognize unusual hand orientations correctly.
* The webcam feed is processed locally.

## 👨‍💻 Author

**Muhammad Adeel**

AI / ML | Python | Computer Vision | Generative AI

⭐ If you find this project useful, consider giving the repository a star.

## 📚 References

* [MediaPipe](https://ai.google.dev/edge/mediapipe)
* [OpenCV](https://opencv.org/)
* [Python](https://www.python.org/)

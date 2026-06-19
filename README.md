# AI-Powered Virtual Mouse Using Hand Gestures

An innovative computer vision application that allows users to control their computer's mouse cursor and perform actions (like clicking) using real-time hand gestures captured via a webcam. This project eliminates the need for a physical hardware mouse by leveraging advanced hand-tracking artificial intelligence.

---

## 🚀 Features

* **Smooth Cursor Movement:** Tracks your index finger landmark in real-time to move the mouse pointer across your screen seamlessly.
* **Gesture Actions:** Perform left-clicks and other mouse actions by bringing specific fingers together (e.g., pinching the index and middle finger).
* **Low Latency:** High-fidelity tracking optimized for a highly responsive, real-time user experience.
* **Hardware-Free:** Works entirely using your computer's built-in webcam or any standard USB camera.

---

## 🛠️ Tech Stack & Dependencies

The project is written entirely in **Python** and utilizes the following core frameworks:

* **OpenCV (`opencv-python`):** For capturing video frames from the webcam and handling image processing.
* **MediaPipe:** Google's open-source framework used for high-fidelity hand landmark detection and tracking.
* **PyAutoGUI:** For programmatically controlling and simulating mouse movements and clicks based on hand coordinates.

---

## 📦 Installation & Setup

Follow these steps to get the project up and running on your local machine:

### 1. Clone the Repository
```bash
git clone [https://github.com/AT4455/Virtual-mouse-using-hand-gestere.git](https://github.com/AT4455/Virtual-mouse-using-hand-gestere.git)
cd Virtual-mouse-using-hand-gestere
## 2.nstall Required Packages
Ensure you have Python installed, then run the following command to install the required dependencies:
pip install opencv-python mediapipe pyautogui
## 3.Run the Application
Execute the main script to start the application and activate your webcam:
python main.py
🎮 How It Works & Gestures
Move Cursor: Raise your Index Finger and move it around the camera viewport to guide the mouse pointer on your screen.

Left Click: Bring your Index Finger and Middle Finger close together (pinch gesture) to trigger a mouse click action.

Tip: You can customize or add new gesture mappings (like right-clicks or scrolling) by modifying the logic inside FINGERTOCURSOR.py.
📁 Project Structure
main.py — The primary entry point of the program that handles the webcam initialization and the core frame processing loop.

FINGERTOCURSOR.py — Contains the background logic for hand tracking, calculating screen coordinate mappings, and executing gesture actions.

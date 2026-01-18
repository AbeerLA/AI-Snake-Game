# 🐍 AI Snake Game (Hand Tracking)

An interactive **Snake Game controlled by hand gestures**, built using **Python**, **OpenCV**, **MediaPipe**, and **CVZone**.  
The snake is controlled using your **index finger**, detected through the webcam in real time.

---

## 🎮 How the Game Works
- The webcam tracks your hand using **MediaPipe Hand Tracking**
- The snake follows the movement of your **index finger**
- The goal is to control the snake and collect food while it grows in length
- The game updates dynamically based on hand movement

---

## 🚀 Features
- Real-time hand tracking  
- Snake movement controlled by finger position  
- Dynamic snake length growth  
- Food rendered using transparent PNG overlay  
- Smooth motion using distance-based calculations  

---

## 🛠 Technologies Used
- Python  
- OpenCV  
- MediaPipe  
- CVZone  
- Math & Random modules  

---

## 📷 Controls
| Action | Control |
|------|--------|
| Move snake | Index finger movement |
| Camera | Webcam (Selfie mode) |

---

## 📁 Project Structure
Snake-Game-AI

├── snake_game.py

├── apple.png

└── README.md


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

git clone https://github.com/your-username/your-repo-name.git

### 2️⃣ Install required libraries
```bash
pip install opencv-python mediapipe cvzone
```
### 3️⃣ Run the game

python snake_game.py


### ⚠️ Make sure:

Your webcam is connected

apple.png is in the same directory as the Python file

### 🧠 What I Learned

Using MediaPipe for real-time hand tracking

Controlling game logic using hand landmarks

Applying geometry (distance calculation) for smooth movement

Integrating OpenCV with CVZone overlays

### 📌 Notes

If the camera does not open, try changing the camera index:
```bash
cap = cv2.VideoCapture(0)
```

Best performance in a well-lit environment

### 🙌 Acknowledgments

This project was built as a learning experience to explore computer vision, AI interaction, and gesture-controlled games using Python.

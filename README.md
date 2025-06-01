# gesturecontrol_game
# 🕹️ Gesture-Controlled Car Racing Game using MediaPipe

Control a racing game using just your hands! This project uses **MediaPipe** to detect hand landmarks via webcam and maps specific gestures to keyboard keys like `W`, `A`, and `D` for moving straight, turning left, or right. No keyboard needed — your palm is the controller!

---

## 🎯 Features

- 👋 Real-time hand tracking with MediaPipe
- 🧠 Gesture logic based on hand landmark geometry
- 🎮 Maps gestures to car game controls (`W`, `A`, `D`)
- 🖥️ Compatible with keyboard-controlled PC games
- 🛠️ Easily extendable to other gestures or actions

---

## 📦 Requirements

Install the necessary packages with:
pip install -r requirements.txt

🧰 Tech Stack
Component	Description
OpenCV	Access webcam and render real-time feed.
MediaPipe	Google’s hand tracking system.
keyboard	Simulate keyboard key presses.
math	Gesture angle calculation.

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/gesture-car-control.git

cd gesture-car-control

Install dependencies:

pip install -r requirements.txt

Run the script:

python main.py

Play your game (like Chrome Dino or Subway Surfers) and control it using hand gestures!
---
#🎮 Gesture Controls
---
Gesture	Action

Hand tilted right	Press D (turn right

Hand tilted left	Press A (turn left)

Hands aligned or centered	Press W (move straight)

(Optional) One hand shown	Move back (press S) — disabled by default

✨ You can customize gestures by editing the landmark comparison logic in main.py.

🧑‍💻 Author
-Anandu Biny
--AI and Data Science Enthusiast
GitHub: @Anandu1709

📜 License

This project is licensed under the MIT License.


---

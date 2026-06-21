# 👀 Mouse Eye Control

Control your computer mouse cursor using eye movements and blink detection.

This project uses computer vision and facial landmark tracking to detect eye movement through a webcam and translate it into mouse cursor actions. It enables hands-free cursor control and can be useful for accessibility applications and human-computer interaction projects.

---

## 🚀 Features
- Move mouse cursor using eye movement
- Blink detection for mouse clicks
- Real-time webcam processing
- Facial landmark detection
- Hands-free computer interaction

---

## 🛠️ Technologies Used

- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- NumPy

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/mouse_eye_controll.git
cd mouse_eye_controll
```

### 2. Create a virtual environment (optional)

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install opencv-python mediapipe pyautogui numpy
```

---

## ▶️ Usage

Run the application:

```bash
python main.py
```

### Controls

- Move your eyes to control the cursor position.
- Blink to perform mouse clicks.
- Press `Esc` or close the webcam window to exit.

---

## 📂 Project Structure

```text
mouse_eye_controll/
│
├── main.py
└── README.md
```

---

## ⚙️ How It Works

1. Captures live video from your webcam.
2. Detects facial landmarks using MediaPipe.
3. Tracks eye position in real time.
4. Maps eye movement to screen coordinates.
5. Detects blinks and triggers mouse click events.

---

## 🎯 Applications

- Accessibility tools
- Hands-free computer control
- Human-computer interaction research
- Assistive technology projects

---

## 🔮 Future Improvements

- Right-click support
- Double-click detection
- Cursor smoothing
- Multi-monitor support
- Calibration system
- Improved blink accuracy

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Debajeet Mandal**

GitHub: https://github.com/Debajeet-1411

If you found this project useful, consider giving it a ⭐ on GitHub!

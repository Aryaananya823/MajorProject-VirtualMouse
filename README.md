

---

```markdown
# 🖱️ Virtual Mouse Pointer using Hand Gesture Recognition

This project demonstrates a Virtual Mouse System that allows users to control the mouse pointer using hand gestures detected via a webcam. It leverages OpenCV and MediaPipe to track hand movements and translate them into mouse cursor actions like movement, click, and drag — offering a contactless, innovative way to interact with a computer.

---

## 🚀 Features

- 👋 Real-time hand tracking using webcam
- 🖐️ Cursor movement based on index finger position
- 👆 Click detection using finger distance logic (e.g., index + thumb)
- 🤏 Drag functionality through pinch gestures
- 📷 Uses OpenCV and Google’s MediaPipe for high-speed gesture detection

---

 🛠️ Tech Stack

- Python
- OpenCV
- MediaPipe
- PyAutoGUI

---

📂 Project Structure

```
MajorProject-VirtualMouse/
├── virtual_mouse.py       # Main script for gesture-based mouse control
├── requirements.txt       # List of dependencies
└── README.md              # Project documentation
```

---

## 🔧 Installation

01. Clone the repository
```bash
git clone https://github.com/Aryaananya823/MajorProject-VirtualMouse.git
cd MajorProject-VirtualMouse
```

2. Install required packages
```bash
pip install -r requirements.txt
```

3. **Run the application**
```bash
python virtual_mouse.py
```

---

 🎥 How It Works

- The webcam captures your hand in real time.
- MediaPipe detects hand landmarks.
- The position of the index finger is mapped to the screen resolution.
- Gestures like thumb and index finger together trigger a click.
- Movements and clicks are executed using PyAutoGUI.

---

 🧠 Future Scope

- 🤖 Use machine learning to recognize more complex hand gestures
- 🎙️ Integrate voice command features
- 🌐 Build a GUI and deploy as a desktop application
- 🖥️ Extend support for multi-monitor setups
- 👩‍🦽 Improve accessibility features for disabled users

---

 ⚠️ Limitations

- Requires good lighting conditions for accurate detection
- Performance may degrade with cluttered backgrounds
- May not work effectively with multiple hands or overlapping objects
- Hardware-dependent (requires a good webcam and sufficient system resources)

---

 📚 References

- [OpenCV Documentation](https://docs.opencv.org/)
- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html)
- [PyAutoGUI Documentation](https://pyautogui.readthedocs.io/)
- Various research papers on gesture recognition and HCI

---

 📝 License

This project is licensed under the MIT License. Feel free to use, modify, and distribute.

---

 🙋‍♀️ Author

```

---

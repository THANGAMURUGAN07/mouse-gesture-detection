# mouse-gesture-detection
🖐️ AI Virtual Mouse using Hand Gestures
This project enables you to control your computer mouse using only hand gestures captured through a webcam. By leveraging MediaPipe, OpenCV, and pyautogui, this virtual mouse can detect and perform various actions like:

✨ Features
Cursor Movement: Move your index finger to control the cursor.

Left Click: Specific gesture for single left click.

Right Click: Specific gesture for right click.

Double Click: Recognized gesture for double-clicking.

Screenshot: Take a screenshot with a distinct gesture.

🧠 Technologies Used
mediapipe for real-time hand tracking.

opencv-python for capturing and displaying webcam frames.

pyautogui and pynput for controlling mouse and taking screenshots.

numpy for gesture calculations and vector math.

📁 Files
main.py: Main script for gesture detection and mouse interaction.

util.py: Helper functions to compute angles and distances between landmarks.

requirements.txt: All required dependencies for this project.

▶️ How to Run
1.Install the requirements:
pip install -r requirements.txt

2.Run the application:
python main.py
Make hand gestures in front of your webcam to control the mouse.


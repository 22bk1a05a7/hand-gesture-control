🖐️ Hand Gesture Control System for Tab, Slide, Volume, Cursor & Shutdown
This project introduces a contactless gesture-based control system that allows users to perform a variety of essential computer operations using only hand gestures. Designed using real-time computer vision and hand tracking, the system provides a more intuitive and hygienic method for human-computer interaction.

🎯 Key Features
🖱️ Cursor Control
Move the mouse pointer by simply moving your hand in front of the camera — allowing full control without touching a mouse.

🔊 Volume Control
Adjust system volume up or down using specific gestures or vertical hand movement.

📑 Slide Navigation
Navigate through presentation slides using swipe gestures (left/right hand movements).

❌ Close Tab/Window
Instantly close browser tabs or application windows using a specific gesture (e.g., a "pinch and drag" or "cross" motion).

⏻ System Shutdown
Execute system shutdown by holding a specific gesture for a few seconds (e.g., open palm or fist).

🛠️ Technologies Used
Python – Core programming language.

OpenCV – Captures and processes webcam feed.

MediaPipe – Detects and tracks hand landmarks with high accuracy.

PyAutoGUI / OS / Pycaw – For simulating system actions like mouse movement, key presses, volume control, and shutdown.

⚙️ How It Works
Real-time Video Feed: Captured via webcam.

Hand Landmark Detection: MediaPipe identifies finger and palm positions.

Gesture Interpretation: Based on landmark positions and movements, the system recognizes user intent.


💡 Applications
Hands-free presentation control

Gesture-based browsing and media control

Accessibility solutions for physically challenged users

Smart classrooms or touchless kiosk interfaces

COVID-safe human-computer interaction


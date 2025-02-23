**Gesture-Based Volume Control Using OpenCV & MediaPipe**

Control your system volume using simple hand gestures! This project leverages OpenCV and MediaPipe Hands to track finger positions and adjust volume dynamically.


**Features**

✅ Real-time hand tracking using MediaPipe
✅ Adjusts system volume based on thumb-index finger distance
✅ Works smoothly with webcams
✅ Uses pycaw for system volume control

**Tech Stack**

Python 🐍
OpenCV 🎥
MediaPipe 🖐
pycaw 🎵

**Demo**
![Screenshot 2025-02-23 104756](https://github.com/user-attachments/assets/c3be5115-2f1c-474d-a884-f56c730869a4)

**Usage**

Bring your thumb and index finger close to lower the volume 🔉
Move them apart to increase the volume 🔊
Press 'q' to exit

**Code Overview**

The script captures video from the webcam and uses MediaPipe Hands to detect hand landmarks. It then calculates the distance between the thumb and index finger and maps it to the system volume range using pycaw.

**Key Functions:**

Hand Tracking: Uses MediaPipe to detect hand landmarks in real-time.
Distance Calculation: Computes the Euclidean distance between the thumb and index finger.
Volume Mapping: Maps the distance to the system's volume range and sets the volume accordingly.
Real-Time Adjustment: Continuously updates the volume based on hand gestures.

**Contribute**

Feel free to fork and improve the project! 🎉

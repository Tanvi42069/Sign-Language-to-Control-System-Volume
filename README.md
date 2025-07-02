Sign Language to Control System Volume
Used hand gesture recognition with MediaPipe and OpenCV to control system volume in real time. By tracking the distance between thumb and index finger, the system adjusts volume dynamically. Integrated Pycaw for audio control, enabling touchless, intuitive interaction.

Features
Real-time hand gesture recognition using MediaPipe
Dynamic volume control by measuring the distance between thumb and index finger
Touchless interaction for adjusting system volume
Integration with Pycaw for seamless audio management
Intuitive and user-friendly interface
Demo
Demo GIF or Screenshot
(Add a demo gif or screenshot here if available)

Requirements
Python 3.7+
OpenCV
MediaPipe
Pycaw
Numpy
Install dependencies with:

bash
pip install opencv-python mediapipe pycaw numpy
Usage
Clone the repository:
bash
git clone https://github.com/Tanvi42069/Sign-Language-to-Control-System-Volume.git
cd Sign-Language-to-Control-System-Volume
Run the main script:
bash
python main.py
Show your hand in front of the webcam:
Move your thumb and index finger closer to decrease the volume.
Move them farther apart to increase the volume.
How It Works
The system uses MediaPipe to detect hand landmarks in the webcam feed.
It calculates the distance between the tips of the thumb and index finger.
This distance is mapped to the system's audio volume using Pycaw.
OpenCV is used for real-time video processing and visual feedback.
Acknowledgements
MediaPipe
OpenCV
Pycaw
License
MIT License



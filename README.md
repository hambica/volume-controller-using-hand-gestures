This project uses computer vision and hand tracking to control system volume with hand gestures. Specifically:
-> It captures live video from the webcam.
-> Detects hand landmarks using MediaPipe.
-> Measures the distance between the thumb and index finger.
-> Maps that distance to the system's volume range using pycaw.
-> Provides real-time visual feedback on the volume level.

Touch-free interaction: Ideal for use in hygienic environments or during tasks where hands are occupied.
Accessibility: Helps users with mobility challenges or temporary limitations to control audio easily.
Tech demo: Showcases integration of computer vision and audio control


-> install the required libraries:
pip install opencv-python mediapipe comtypes pycaw numpy

->Connect a webcam (if not already integrated).

-> Run the script:
python volume_control_using_hand_gesture.py
-> Use your thumb and index finger to control the volume by changing the distance between them in front of the camera.

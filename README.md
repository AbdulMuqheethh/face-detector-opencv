Real-Time Face Detector
A real-time face detection app built with Python and OpenCV. It uses your webcam to detect faces live and draws bounding boxes around them with a face count on screen.
What it does

Opens your webcam feed live
Detects faces in real time using OpenCV's Haar Cascade classifier
Draws a green box around every face detected
Shows a live count of how many faces are on screen
Press Q to quit

Built with

Python 3.11
OpenCV (cv2) — for camera access and face detection

How to run
Step 1 — Install OpenCV
pip install opencv-python
Step 2 — Run the script
python mood.py
How it works
The script captures frames from your webcam one by one. Each frame is converted to grayscale and passed through OpenCV's pre-trained Haar Cascade face detection model. When a face is found, a green rectangle is drawn around it and the face count is updated on screen in real time.
What I learned

How webcam capture works in Python using OpenCV
What image frames are and how they're processed
How pre-trained computer vision models work
How to display real time overlays on a video feed

What's next

Adding real time emotion detection (happy, sad, angry, surprised)
Deploying on a Raspberry Pi as a standalone device
Adding motion detection and phone alerts via Telegram


Built by Abdul Muqheeth

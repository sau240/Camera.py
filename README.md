Face Detection with OpenCV
This project uses OpenCV to detect faces from a live webcam feed, draw a bounding box around detected faces, and save the image locally.

Features
Captures an image from the webcam.

Converts it to grayscale for better face detection.

Uses OpenCV's Haar Cascade Classifier to detect faces.

Draws a green rectangle around detected faces.

Saves the captured image as captured_face.jpg.

Requirements
Make sure you have the following installed:

Python 3.x

OpenCV (pip install opencv-python)

How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/Face-Detection.git
cd Face-Detection
Install dependencies:

bash
Copy
Edit
pip install opencv-python
Run the script:

bash
Copy
Edit
python face_detection.py


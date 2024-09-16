# face_detection-using-haarcascade
Face Detection Project
**Overview**
This project demonstrates face detection using OpenCV and Haar cascades. It utilizes a pre-trained Haar cascade classifier to detect faces in an image and visualizes the detected faces by drawing rectangles around them. The processed image is then displayed using Matplotlib.

**Requirements**
Python 3.x
OpenCV
NumPy
Matplotlib
You can install the required packages using pip:
pip install opencv-python numpy matplotlib
**Usage**
Prepare Your Image: Place the image you want to process in the same directory as your script and name it face.jpg. You can modify the filename in the script if your image has a different name.
Run the Script: Execute the script using Python:
python face_detection.py
**View Results:**
The script will read the image, detect faces, draw rectangles around them, and display the resulting image.
**Notes**
Ensure that the haarcascade_frontalface_default.xml file is available in your OpenCV installation's haarcascades directory.
Adjust the scaleFactor and minNeighbors parameters in the detectMultiScale function to improve detection results depending on the image.
**License**
This project is licensed under the MIT License - see the LICENSE file for details.

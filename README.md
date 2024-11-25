# Face Detection with OpenCV
- This project demonstrates how to perform face detection in images using OpenCV's Haar Cascade Classifier. It utilizes Python's opencv-python library to process images and detect faces.

# Installation
- To get started, install the necessary Python package:
- pip install opencv-python

# Modules Used:
- OpenCV (opencv-python): For image processing and face detection.
- Matplotlib: For visualizing the results within a Jupyter notebook.

# Steps:
1. Read the image: Load the image using cv2.imread().
2. Convert to Grayscale: Convert the image to grayscale using cv2.cvtColor() for face detection.
3. Face Detection: Use OpenCV's pre-trained Haar Cascade classifier to detect faces in the image with detectMultiScale().
4. Draw Rectangles: Highlight the detected faces by drawing green rectangles around them using cv2.rectangle().
5. Display the Image: Show the image with detected faces using matplotlib.pyplot.imshow().

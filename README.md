# POSE DETECTION USING MEDIAPIPE

# PROJECT OVERVIEW
- This project demonstrates real-time pose detection using the Mediapipe library in Python. The goal is to utilize the webcam to detect and visualize human body pose landmarks and connections in a live video feed. Mediapipe’s pose detection model is used to track body movements and draw landmarks on the detected poses.

# CODE PIPELINE SUMMARY(Steps Taken)

## 1.  Setup and Dependencies:
-  Installed the Mediapipe library.
-  Imported necessary libraries including cv2 for handling webcam input and mediapipe for pose detection.

## 2.  Webcam Initialization:
- Identified and initialized the webcam using OpenCV's VideoCapture.

## 3.  Pose Detection Setup:
-  Configured Mediapipe's pose detection model and drawing utilities.
-  Optionally adjusted parameters for pose detection (e.g., min_detection_confidence, min_tracking_confidence).

## 4.  Real-Time Pose Detection Loop:
-  Captured frames from the webcam.
-  Converted frames from BGR to RGB format.
-  Applied the Mediapipe pose detection model to identify body pose landmarks.
-  Drew the detected landmarks and connections on the frame.
-  Displayed the processed frame with annotations in a window.

## 5.  Termination:
-  Implemented a loop to continuously process frames until a keypress ('p') is detected.
-  Released the webcam capture and closed all OpenCV windows after the process.

# KET ACHIEVEMENTS
1.  Successfully implemented real-time pose detection using the Mediapipe library.
2.  Visualized body pose landmarks and connections directly on the video feed.
3.  Created a user-friendly display with text annotations for project identification.

# CONCLUSION
-  This project effectively demonstrates the use of Mediapipe for pose detection, providing a powerful tool for real-time body tracking and visualization. The integration of webcam input and Mediapipe’s pose detection capabilities enables interactive and dynamic pose detection experiences. Future enhancements could include additional pose analysis or integration with other computer vision applications.

# TECH STACK
-  Jupyter Notebook
-  Webcam

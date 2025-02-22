# Synthetic-Lane-Detection-Project
Synthetic Lane Detection Project

Overview

This project generates a synthetic lane detection video and applies basic lane detection using edge detection techniques. The synthetic video simulates a road with lane markings, and the detection algorithm processes the video to extract lane boundaries.

Objectives

Generate a synthetic road video with lane markings.

Detect lane boundaries using edge detection techniques.

Display processed frames with detected lanes.

Implementation Details

1. Synthetic Lane Video Generation

A grayscale road is created with two white lane markings.

The lane markings have slight movement to simulate real-world conditions.

The video is generated using OpenCV and saved as lane_video.mp4.

2. Lane Detection Algorithm

The video is loaded frame-by-frame.

Each frame is converted to grayscale.

Gaussian blur is applied to smooth the image.

Canny edge detection is used to extract lane boundaries.

The processed frames are displayed using cv2_imshow() in Google Colab.





Applications

Understanding computer vision techniques for lane detection.

Developing autonomous vehicle perception systems.

Extending the project to real-world datasets for advanced lane detection.

Future Improvements

Use deep learning models for more robust lane detection.

Implement Hough Transform to detect lane lines.

Apply perspective transformation to improve detection accuracy.


# Vision to Voice: Real-Time Object Detection with YOLOv8 and TTS
Vision to Voice is a real-time object detection system that uses YOLOv8 for detecting objects and provides audio feedback about detected objects using text-to-speech technology.

Overview
This project detects objects in real-time using a webcam or a video and announces the closest object's type and location through voice guidance. It is designed to assist users by combining vision-based detection with audio feedback.

Features
Real-time object detection and annotation.
Audio feedback for objects detected within a specific range.
Custom-trained YOLOv8 model for improved detection.
Simple and user-friendly implementation.
Installation
To use this project, you will need Python installed on your system along with necessary libraries. Install required packages using pip, including ultralytics, gTTS, and OpenCV.

Ensure your system has a webcam for live detection or use a pre-recorded video for testing.

Usage
Load the custom-trained YOLOv8 model provided in the project.
Run the live detection script to use your webcam for object detection.
The system will detect objects, display bounding boxes with labels, and announce close objects via text-to-speech.
Press 'q' to exit the detection mode when running live.
Customization
You can modify:

The distance threshold for audio feedback.
The classes of objects detected and their categories.
The model file path to use your own trained model.
Known Issues
Ensure all dependencies are installed correctly. Mismatched versions may cause errors.
Webcam access may require system permissions.
Some objects may have less accurate detections depending on the model.
Contributing
Contributions to improve this project are welcome. Feel free to submit issues or pull requests on the GitHub repository.

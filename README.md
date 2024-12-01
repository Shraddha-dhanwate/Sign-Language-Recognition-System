# Overview
This project bridges the communication gap between sign language users and non-signers by providing a real-time system that recognizes American Sign Language (ASL) gestures. Using AI, computer vision, and machine learning, it translates ASL gestures into text and speech, enabling seamless communication and fostering inclusivity for the deaf and hard-of-hearing community.

# Key Features
**Real-Time Gesture Recognition**
1. Captures hand gestures using a webcam.
2. Detects hand landmarks with MediaPipe Hands for high accuracy.

   
**Text and Speech Output**
1. Recognized gestures are displayed as text in a user-friendly GUI.
2. Converts gestures into speech using a text-to-speech engine for better accessibility.

**Wide Range of Gesture Support**

Recognizes ASL alphabets (A-Z), numbers (0-9), and common phrases like "Hello," "Yes," "No," and "Thanks."

**Interactive GUI**
1. Built with Tkinter for real-time text updates.
2. Includes features like text clearing and easy exit controls.

**Efficient AI Model**

Uses a pre-trained supervised learning model with logistic regression for reliable and fast predictions.

# How It Works
**Input Capture:** The system captures video input via a webcam.
**Hand Detection:** Hand landmarks are detected and normalized using MediaPipe Hands.
**Gesture Prediction:** The ML model predicts the corresponding ASL gesture.
**Output:**
Text is displayed on the GUI.
Speech feedback is provided using a text-to-speech engine.
# Requirements
Python 3.8+, 
OpenCV,
MediaPipe,
Tkinter,
NumPy,
pyttsx3,
Pickle
# Future Enhancements
1. Expand support for more sign languages.
2. Improve robustness under varying lighting conditions.
3. Optimize the system for mobile platforms.
   
This project aims to empower the deaf and hard-of-hearing community by making communication more accessible and inclusive. Contributions and suggestions are welcome!



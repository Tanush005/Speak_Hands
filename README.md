# Speak_Hands
Sign Language to Text & Speech Translator

Overview:
This project is a deep learning–powered human-computer interface (HCI) that recognizes American Sign Language (ASL) hand gestures from a webcam feed, translates them into text, and vocalizes them in real time. It is designed to bridge the communication gap for deaf and hard-of-hearing individuals and those unfamiliar with sign language.

Key Features:

Hand gesture detection using MediaPipe and OpenCV.

Gesture classification using a Convolutional Neural Network (CNN) built with Keras and TensorFlow.

Real-time text translation of detected gestures.

Speech output using the pyttsx3 text-to-speech library.

User-friendly GUI implemented with Tkinter.

Robust to varied backgrounds and lighting conditions by extracting hand landmarks and processing them on a plain canvas.

Tech Stack:

Language: Python 3.8+

ML Framework: TensorFlow, Keras

Hand Tracking: MediaPipe, OpenCV

Speech: pyttsx3

GUI: Tkinter

System Pipeline:

Webcam captures hand gesture.

MediaPipe detects hand and extracts landmarks.

Landmarks are drawn on a white background, removing dependence on lighting or environment.

CNN classifies the gesture into corresponding alphabet groups, followed by refinement to individual letters.

Predicted letter displayed as text and spoken using a speech engine.

ASL Alphabet Chart:
![ASL-Alphabet-ASDC-web](https://github.com/user-attachments/assets/1d3997a1-b449-409b-bea5-099483d0462b)

Future Scope:

Develop an Android application to make this solution more portable.

Add multi-language support for speech output.

Extend the system to predict entire words and sentences, not just single alphabets.

Closing Note:
By using this system, you’re not just interacting with software — you’re experiencing a glimpse of how technology can promote accessibility and inclusivity for millions around the world. If you find this project useful or inspiring, please consider sharing it or contributing to its future development.

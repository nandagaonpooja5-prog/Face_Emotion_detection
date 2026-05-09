# Face_Emotion_detection
# Project Title

## Real-Time Multi-Face Emotion Detection System

---

# Brief One Line Summary

* A real-time AI-powered system that detects multiple faces simultaneously and predicts facial emotions with confidence scores using Computer Vision and Deep Learning.

---

# Overview

* This project is a Real-Time Multi-Face Emotion Detection System developed using OpenCV, DeepFace, CNN concepts, and Deep SORT tracking.
* The system captures live webcam video, detects multiple human faces, tracks them in real time, and predicts emotions with confidence scores.
* The project demonstrates the practical implementation of Computer Vision and Deep Learning for real-time AI applications.

---

# Problem Statement

* Human emotions play an important role in communication and behavior analysis.
* Traditional systems cannot efficiently monitor emotions in real time for multiple individuals simultaneously.
* The objective of this project is to build a real-time system capable of:

  * Detecting multiple faces
  * Tracking individuals continuously
  * Predicting facial emotions accurately
  * Displaying confidence scores in live video feed

---

# Dataset

* The project uses pre-trained DeepFace emotion recognition models trained on facial expression datasets.
* Live webcam frames are used as real-time input for prediction.

Supported emotions include:

* Happy
* Sad
* Angry
* Neutral
* Fear
* Surprise
* Disgust

---

# Tools and Technologies

## Programming Language

* Python

## Libraries and Frameworks

* OpenCV
* DeepFace
* NumPy
* Matplotlib
* Deep SORT Realtime
* Collections

## Concepts Used

* Computer Vision
* Deep Learning
* Convolutional Neural Networks (CNN)
* Facial Emotion Recognition
* Real-Time Face Tracking
* Confidence Score Prediction

---

# Methods

## 1. Video Capture

* Captures real-time webcam feed using OpenCV.

## 2. Face Detection

* Detects multiple faces from each frame.

## 3. Face Tracking

* Uses Deep SORT algorithm to assign unique tracking IDs.
* Maintains stable tracking across frames.

## 4. Emotion Recognition

* DeepFace analyzes facial expressions.
* Predicts emotions using CNN-based deep learning models.

## 5. Confidence Score Prediction

* Displays confidence score percentage for predicted emotion.

## 6. Real-Time Visualization

* Draws bounding boxes, tracking IDs, emotion labels, and confidence scores on live video feed.

---

# Key Insights

* Real-time emotion recognition requires optimized frame processing.
* Multi-face tracking improves consistency and reduces identity switching.
* Confidence scores help evaluate prediction reliability.
* CNN-based emotion recognition performs effectively in live environments.
* Lighting conditions and face angles impact prediction accuracy.

---

# Dashboard / Model / Output

## Live Output Includes:

* Face Bounding Boxes
* Tracking IDs
* Predicted Emotions
* Confidence Scores
* Real-Time Face Tracking

## Example Output

```text
ID 1 -> Happy (94%)
ID 2 -> Neutral (87%)
ID 3 -> Angry (79%)
```

---

# How to Run this Project?

## Step 1: Clone Repository

```bash
git clone <repository-link>
cd <repository-folder>
```

## Step 2: Install Required Libraries

```bash
pip install opencv-python
pip install deepface
pip install numpy
pip install matplotlib
pip install deep-sort-realtime
```

## Step 3: Run the Project

```bash
python app.py
```

## Step 4: Webcam Activation

* The webcam opens automatically.
* Real-time emotion detection starts immediately.

---

# Results & Conclusion

## Results

* Successfully detects multiple faces simultaneously.
* Performs real-time facial emotion prediction.
* Tracks faces continuously using Deep SORT.
* Displays confidence scores for each prediction.
* Achieves stable real-time AI inference.

## Conclusion

* The project demonstrates practical implementation of Computer Vision and Deep Learning techniques for real-time emotion analysis.
* Integration of OpenCV, DeepFace, and Deep SORT enables efficient multi-face tracking and emotion prediction.
* The system showcases real-world AI application development skills.

---

# Future Work

* Improve low-light detection performance
* Add emotion history analytics dashboard
* Integrate voice emotion recognition
* Deploy using Streamlit or Flask
* Add GPU acceleration
* Store emotion logs in database
* Improve tracking stability and FPS optimization
* Add emotion trend visualization

---

# Author & Contact

## Author

* Pooja Nandagaon

## GitHub

* Add your GitHub profile link here

## LinkedIn

* Add your LinkedIn profile link here

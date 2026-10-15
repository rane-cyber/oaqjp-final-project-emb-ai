# Final Project

## Emotion Detector Web Application

This repository contains the final project code for the Emotion Detection application built using Python, Flask, and IBM Watson NLP libraries.

### Overview
The Emotion Detector application analyzes the input text provided by the user and determines the scores for five key emotions:
- Anger
- Disgust
- Fear
- Joy
- Sadness

It also identifies the **dominant emotion** from the output.

### Features
- Embedded AI integration using Watson NLP Emotion Predict function.
- Python packaging under the `EmotionDetection` package.
- Unit testing with Python `unittest`.
- Web interface built using Flask framework.
- Robust error handling for invalid or blank inputs (HTTP status 400 handling).
- Code formatted and checked against `pylint` standards for a clean 10/10 score.

### Setup & Execution

1. **Run Unit Tests:**
   ```bash
   python3 test_emotion_detection.py

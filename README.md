# Emotion Detector - Final Project

## Project Name: Emotion Detector using Watson NLP and Flask

This project is the final project for the **Developing AI Applications with Python and Flask** course on Coursera (IBM).

## Overview

The Emotion Detector is an AI-based web application that uses the Watson NLP EmotionPredict service to analyze text and return emotional analysis scores including anger, disgust, fear, joy, and sadness — along with the **dominant emotion**.

## Features

- Detect emotions from text input using IBM Watson NLP
- Returns scores for: `anger`, `disgust`, `fear`, `joy`, `sadness`
- Identifies the `dominant_emotion` with the highest score
- Web interface built with Flask
- Error handling for blank/invalid input
- Unit tested with Python `unittest`
- Static code analysis with `pylint`

## Project Structure

```
oaqjp-final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── static/
│   └── mywebscript.js
├── server.py
├── test_emotion_detection.py
└── README.md
```

## Setup & Installation

```bash
pip install flask requests
python server.py
```

## Usage

1. Run the Flask server: `python server.py`
2. Open browser at `http://localhost:5000`
3. Enter text and click **Run Sentiment Analysis**

## Tasks Completed

- [x] Task 1: Clone repository
- [x] Task 2: Create emotion detection application
- [x] Task 3: Format the output
- [x] Task 4: Package as EmotionDetection module
- [x] Task 5: Unit tests
- [x] Task 6: Flask web deployment
- [x] Task 7: Error handling
- [x] Task 8: Static code analysis (pylint)

## Author

Apurva | GitHub: [Apurva-jpg963](https://github.com/Apurva-jpg963)

# Final Project

A web application developed with Python, Flask, and IBM Watson NLP to predict emotions from textual input.

## Features
- Analyzes text for emotion scores: **anger**, **disgust**, **fear**, **joy**, and **sadness**.
- Determines the **dominant emotion** from the input text.
- Provides a clean user interface deployed using Flask.
- Robust error handling for invalid or blank text entries.
- Validated with unit tests and compliant with PEP 8 standards.

## Project Structure
```text
oaqjp-final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── server.py
├── test_emotion_detection.py
└── README.md
```

## Setup and Running
1. Install dependencies:
   ```bash
   pip install flask requests
   ```
2. Run unit tests:
   ```bash
   python3 test_emotion_detection.py
   ```
3. Start the Flask server:
   ```bash
   python3 server.py
   ```
4. Access the web application at `http://127.0.0.1:5000/`.

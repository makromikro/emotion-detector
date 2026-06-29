Emotion Detection Web Application
Overview

This project is an AI-powered web application developed using Python, Flask, and IBM Watson Natural Language Processing (NLP).

The application allows users to enter a sentence describing their feelings. It analyzes the text using the IBM Watson Emotion Detection model and returns confidence scores for five emotions:

Joy
Anger
Sadness
Fear
Disgust

It also identifies the dominant emotion detected in the text.

Features
Emotion detection using IBM Watson NLP
Detects five different emotions
Displays the dominant emotion
Flask-based web interface
Handles invalid or empty user input
Unit testing included
Static code analysis using Pylint
Technologies Used
Python 3
Flask
IBM Watson NLP
Requests
HTML
CSS
JavaScript
unittest
Pylint
Project Structure
EmotionDetection/
│
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
│
├── static/
├── templates/
├── server.py
├── test_emotion_detection.py
├── requirements.txt
└── README.md
Installation

Clone the repository:

git clone https://github.com/makromikro/emotion-detector.git

Move into the project folder:

cd EmotionDetection

Install the required packages:

pip install -r requirements.txt
Running the Application

Start the Flask server:

python server.py

Open your browser and navigate to:

http://localhost:5000
Running Unit Tests
python test_emotion_detection.py
Running Static Code Analysis
pylint server.py
Author

Developed by Burak as part of the IBM Skills Network course:

Developing AI Applications with Python and Flask
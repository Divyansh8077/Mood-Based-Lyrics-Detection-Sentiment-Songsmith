🎶 Mood-Based Lyrics Detection System
📖 Introduction

The Mood-Based Lyrics Detection System is a full-stack Machine Learning application that analyzes song lyrics and predicts the emotional mood expressed in the text using Natural Language Processing (NLP). The project demonstrates the integration of an ML model with a web-based frontend and a Flask-powered backend, providing real-time mood predictions through a clean and interactive interface.

🎯 Problem Statement

Music streaming platforms often rely on audio features or manual tagging for mood classification. This project focuses on text-based emotion detection, extracting emotional context directly from song lyrics to classify moods such as Happy, Sad, Calm, and Energetic.

💡 Solution Overview

The system accepts song lyrics as input from the user, preprocesses the text using NLP techniques, and applies a trained ML classification model to predict the emotional mood. The frontend and backend communicate using RESTful APIs built with Flask, ensuring smooth and real-time interaction.

⚙️ System Architecture

Frontend collects user input and displays results

Flask Backend handles API requests and ML inference

ML Model processes lyrics and predicts mood

NLP Pipeline cleans, tokenizes, and vectorizes text

🛠 Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: Python, Flask

Machine Learning: NLP, Text Preprocessing, Classification Algorithms

Integration: REST APIs

🚀 Key Features

Real-time mood detection from song lyrics

Full-stack integration using Flask

Clean and responsive user interface

Handles noisy and mixed-emotion text data

Modular and scalable code structure

🔄 Workflow

User enters song lyrics on the frontend

Input is sent to the Flask backend via API

Text is preprocessed using NLP techniques

ML model predicts the emotional mood

Predicted mood is returned and displayed

<H1>🎶 Mood-Based Lyrics Detection System</H1>
<H3>📖 Introduction</H3>

The Mood-Based Lyrics Detection System is a full-stack Machine Learning application that analyzes song lyrics and predicts the emotional mood expressed in the text using Natural Language Processing (NLP). The project demonstrates the integration of an ML model with a web-based frontend and a Flask-powered backend, providing real-time mood predictions through a clean and interactive interface.

<H3>🎯 Problem Statement</H3>

Music streaming platforms often rely on audio features or manual tagging for mood classification. This project focuses on text-based emotion detection, extracting emotional context directly from song lyrics to classify moods such as Happy, Sad, Calm, and Energetic.

<H3>💡 Solution Overview</H3>

The system accepts song lyrics as input from the user, preprocesses the text using NLP techniques, and applies a trained ML classification model to predict the emotional mood. The frontend and backend communicate using RESTful APIs built with Flask, ensuring smooth and real-time interaction.

<H3>⚙️ System Architecture</H3>

Frontend collects user input and displays results

Flask Backend handles API requests and ML inference

ML Model processes lyrics and predicts mood

NLP Pipeline cleans, tokenizes, and vectorizes text

<H3>🛠 Tech Stack</H3>

Frontend: HTML, CSS, JavaScript

Backend: Python, Flask

Machine Learning: NLP, Text Preprocessing, Classification Algorithms

Integration: REST APIs

<H3>🚀 Key Features</H3>

Real-time mood detection from song lyrics

Full-stack integration using Flask

Clean and responsive user interface

Handles noisy and mixed-emotion text data

Modular and scalable code structure

<H3>🔄 Workflow</H3>

User enters song lyrics on the frontend

Input is sent to the Flask backend via API

Text is preprocessed using NLP techniques

ML model predicts the emotional mood

Predicted mood is returned and displayed

<img width="775" height="439" alt="image" src="https://github.com/user-attachments/assets/ee5c9f0d-2262-4f4c-aaeb-b0a7b837ef12" />

<H3>▶️ Installation & Setup</H3>
Prerequisites

Python 3.8+

pip

Steps to Run
git clone <repository-link>
cd mood-based-lyrics-detection
pip install -r requirements.txt
python app.py

<H3>📊 Output</H3>

The system displays the predicted emotional mood of the lyrics entered by the user, enabling emotion-aware analysis and recommendations.
<img width="1905" height="902" alt="image" src="https://github.com/user-attachments/assets/a5aaea62-67aa-48ce-b0f8-d110f1125bb6" />
<img width="1878" height="896" alt="image" src="https://github.com/user-attachments/assets/e35a45d1-9afd-4c47-b0af-8c25b8286469" />
<img width="1912" height="960" alt="image" src="https://github.com/user-attachments/assets/62aa8831-75e5-4eb0-a992-5cbe4eaba414" />
<img width="1798" height="898" alt="image" src="https://github.com/user-attachments/assets/35607e15-9f60-40ea-8804-e68f63b10e5c" />


<H3>📌 Use Cases</H3>

Mood-based music recommendation systems

NLP emotion detection demonstrations

Full-stack ML learning and deployment projects

<H3>🧠 Learning Outcomes</H3>

End-to-end ML pipeline development

NLP-based text classification

Flask backend and REST API development

Frontend–backend integration

Real-world data handling and deployment concepts

<H3>🚧 Limitations</H3>

Classification depends only on lyrics (audio features not included)

Performance depends on dataset quality and size

<H3>🔮 Future Enhancements</H3>

Add audio feature-based mood detection

Deploy the application on cloud platforms

Improve model accuracy using deep learning

Add user-based recommendation features




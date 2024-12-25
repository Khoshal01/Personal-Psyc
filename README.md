# Personal-Psyc
A mental health assistant chatbot designed to provide personalized post-surgery rehabilitation exercises, specifically targeting lower body issues like knee problems. The project integrates conversational AI and recovery exercises, helping patients with their physical rehabilitation. Key features include:

Flask Backend: Ensures efficient and scalable operations.
Gradio Chatbot: Provides an intuitive interface for user interactions.
RAG Integration: Uses book-based datasets for meaningful and informative responses.
Exercise Module: Guides patients through knee recovery exercises with real-time feedback powered by OpenCV.

# Features
Post-Surgery Rehabilitation Exercises: Offers specific exercises to help strengthen the knee after surgery.
AI-Powered Chatbot: Provides empathetic responses and psychological guidance for recovery.
Recovery Exercises: Interactive sessions focused on lower body rehabilitation.
Data-driven Responses: RAG ensures accurate and contextual answers.
User-friendly Interface: Built with Gradio for simplicity and accessibility.

# Installation Instructions
Setting Up Backend and Chatbot Separately
1 Clone the repository:
git clone https://github.com/username/personal-psychologist.git
2 Navigate to the project directory:
cd personal-psychologist
3 Create a virtual environment for the backend:
python -m venv venv-backend
venv-backend\Scripts\activate
4 Install backend dependencies:
pip install -r requirements-backend.txt
5 Run the Flask backend:
python app.py
The backend will run on http://localhost:5000

Setting Up the Chatbot
1 Create a virtual environment for the chatbot:
python -m venv venv-chatbot
venv-chatbot\Scripts\activate
2 Install chatbot dependencies:
pip install -r requirements-chatbot.txt
3 Run the Gradio chatbot interface:
python chatbot.py

# How to Use
Backend: Provides the data processing and API for the chatbot.
Chatbot: Interact with the AI-powered chatbot for post-surgery rehabilitation exercises and psychological support.
Exercises: Access the "Exercises" section for knee strengthening routines.

# Technologies Used
Backend: Flask
Chatbot Interface: Gradio
Data Handling: Retrieval-Augmented Generation (RAG)
Computer Vision: OpenCV

#  Screenshots of the Chatbot Interface
![Chatbot Screenshot 1](images/chatbot_screenshot1.png)
![Chatbot Screenshot 2](images/chatbot_screenshot2.png)




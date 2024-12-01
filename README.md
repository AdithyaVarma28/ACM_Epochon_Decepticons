# Suchintana

## Overview
Suchintana is an innovative stress reduction chatbot designed to provide support and lighten the mood through a user-friendly digital interface. The chatbot engages users with interactive conversations, offering humorous and lighthearted responses to help manage stress. Users can chat with the bot to receive a mix of funny jokes, playful banter, and cheerful activities that promote relaxation and laughter. The platform allows users to create profiles and customize their experience, ensuring the content is tailored to their preferences.

## Features
- **User Authentication**: Secure sign-up, sign-in, and session management using hashed passwords.
- **Chat Interface**: Users can send messages and receive AI-generated responses.
- **Profile Management**: Users can update their email or change their password.
- **New Conversation**: Clear chat history for a fresh start.

## Installation Instructions

### Step 1: Clone the Repository
Clone the repository to your local machine:
```bash
git clone https://github.com/AdithyaVarma28/Suchintana
cd frontend
```
Step 2: Install Dependencies

Ensure you have Python 3.8+ installed. Use the following command to install the required libraries:
```bash
pip install -r requirements.txt
```

Step 4: Configure the Application

Update the app.secret_key in app.py for enhanced security.
Replace the api_key in the Hugging Face InferenceClient initialization with your personal Hugging Face API key.

Step 5: Run the Application

Start the Flask application by running:
```bash
python app.py
```
The application will be accessible at http://127.0.0.1:5000.

Configuration

Database: Uses SQLite with the data.db file by default.
AI Model: Utilizes the Hugging Face microsoft/DialoGPT-medium model. Modify the model or parameters in the chat function as needed.
Notes

Ensure the frontend/templates and frontend/static directories contain the necessary HTML and CSS files for the web interface.
Use a virtual environment to isolate dependencies.
Future Enhancements

Add support for additional AI models.
Implement role-based access control.
Enhance UI for a better user experience.
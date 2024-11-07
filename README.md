# Healthcare-Translation-Web-App-with-Generative-AI
## User Guide

Overview

This application allows users to input voice in a selected language, provides a real-time transcript, translates the text into another selected language, and offers the option to play the translated audio. The translation is powered by Gemini, accessed via a Flask API. The front-end is built with React and is mobile web page compatible.

## Features

- Voice Input: Speak in the selected language.
- Real-time Transcription: View the real-time transcript of your speech.
- Translation: Translate the transcript into the selected language.
- Audio Playback: Play the translated text as audio.
- Setup

## Environment Variables:

- REACT_APP_API_PATH: The endpoint for the translation API.
- API_KEY: The API key for authentication (used in the backend).

## Deployment:

- Front-end: Deployed on Vercel.
- Back-end: Deployed on Render with a requirements.txt file for Python dependencies.

## Usage
- Select Input Language: Choose the language you will speak in.
- Select Output Language: Choose the language for translation.
- Start Speech Recognition: Click the "Speak" button to start recording your voice.
- View Transcript: The app will display the real-time transcript of your speech.
- Translate Text: The app will automatically translate the transcript into the selected output language.
- Play Translated Audio: Click the "Play" button to hear the translated text.

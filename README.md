AI-Powered Meeting Summarizer
An AI-driven system that converts meeting audio recordings into concise, structured summaries using Generative AI and Large Language Models (LLMs). This project focuses on real-world meeting productivity by automatically transcribing and summarizing long audio discussions.

Features
Audio-to-text transcription using Whisper

LLM-based meeting summarization (not traditional NLP)

Handles large audio files through intelligent chunking

Fast inference using Groq API

Generates clear, human-like summaries with key discussion points

Tech Stack
Python

OpenAI Whisper (Speech-to-Text)

Groq API (LLM Inference)

Large Language Models (Generative AI)

FFmpeg (Audio Processing)

Flask (API Backend)

How It Works
User uploads a meeting audio file

Audio is preprocessed and split if the file is large

Whisper converts audio into text

Transcribed text is sent to an LLM via Groq API

The system generates a concise meeting summary

Project Structure
MEETING_SUMMARIZER/
│
├── audio/
├── transcripts/
├── summaries/
├── app.py
├── requirements.txt
└── README.md

Installation
Clone the repository

git clone https://github.com/Yasaswini1807/MEETING_SUMMARIZER.git
cd MEETING_SUMMARIZER

Create and activate virtual environment (optional)

python -m venv venv
source venv/bin/activate

Install dependencies

pip install -r requirements.txt

Set environment variable

export GROQ_API_KEY="your_api_key_here"

Usage
python app.py

Upload a meeting audio file and the system will generate a summarized output.

Key Highlights
Uses Generative AI and LLMs instead of traditional NLP

Designed for real-world meeting audio summarization

Supports long-duration meetings

Scalable and production-ready architecture

Future Enhancements
Speaker identification

Multi-language transcription

Web-based dashboard

Action item extraction

Integration with meeting platforms

🎙️ AI-Powered Meeting Summarizer
An AI-driven meeting summarization system that converts audio recordings of meetings into clear, concise, and structured summaries using Large Language Models (LLMs) and speech-to-text technology.

This project is designed to help teams quickly extract key discussion points, decisions, and action items from long meetings—saving time and improving productivity.

🚀 Features
🎧 Audio-to-Text Transcription

Converts meeting audio files into accurate text using Whisper.

🧠 LLM-Based Summarization

Generates human-like summaries using Generative AI (LLMs) instead of traditional NLP.

📌 Structured Output

Produces concise summaries with key points and action items.

⚡ Fast Inference

Uses Groq API for high-speed LLM processing.

📂 Supports Large Audio Files

Handles long meetings by chunking audio intelligently.

🛠️ Tech Stack
Python

OpenAI Whisper – Speech-to-text transcription

Groq API – Fast LLM inference

Large Language Models (LLMs) – Context-aware summarization

FFmpeg – Audio processing

Flask (if used for API / UI)

REST APIs

🧩 How It Works
Upload Meeting Audio

Audio Preprocessing

File validation & chunking for large audio sizes

Speech-to-Text

Audio is transcribed using Whisper

LLM-Based Summarization

Transcribed text is sent to an LLM via Groq API

Final Summary Output

Clean, readable meeting summary is generated

📁 Project Structure
bash
Copy code
MEETING_SUMMARIZER/
│
├── audio/                 # Input audio files
├── transcripts/           # Generated transcriptions
├── summaries/             # Final summarized outputs
├── app.py                 # Main application logic
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
⚙️ Installation & Setup
1️⃣ Clone the Repository
bash
Copy code
git clone https://github.com/Yasaswini1807/MEETING_SUMMARIZER.git
cd MEETING_SUMMARIZER
2️⃣ Create Virtual Environment (Optional but Recommended)
bash
Copy code
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
3️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
4️⃣ Set Environment Variables
bash
Copy code
export GROQ_API_KEY="your_api_key_here"
(Windows PowerShell)

powershell
Copy code
setx GROQ_API_KEY "your_api_key_here"
▶️ Usage
bash
Copy code
python app.py
Upload a meeting audio file

Wait for transcription and summarization

View the generated summary

📌 Key Highlights
❌ No traditional NLP techniques

✅ Fully powered by Generative AI & LLMs

✅ Handles large audio files

✅ Real-world productivity use case

✅ Scalable for enterprise meeting workflows

📈 Future Enhancements
Speaker diarization (who spoke what)

Multi-language support

Web dashboard for uploads and downloads

Action item extraction

Calendar & meeting tool integrations

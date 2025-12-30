
# 🎙️ AI-Powered Meeting Summarizer

An AI-driven system that converts meeting audio recordings into concise, structured summaries using **Generative AI and Large Language Models (LLMs)**. This project is built to solve real-world productivity problems by automatically transcribing and summarizing long meeting recordings.

Unlike traditional NLP-based systems, this project leverages **LLMs, Whisper, and Groq API** to generate human-like, context-aware summaries.

---

## 🚀 Features

- 🎧 Audio-to-text transcription using **Whisper**
- 🧠 Meeting summarization using **LLMs (Generative AI)**
- ⚡ Fast inference powered by **Groq API**
- 📂 Supports large audio files through intelligent chunking
- 📝 Produces clear, structured, and concise summaries
- ❌ No rule-based or traditional NLP techniques

---

## 🛠️ Tech Stack

- **Python**
- **OpenAI Whisper** – Speech-to-Text
- **Groq API** – High-speed LLM inference
- **Large Language Models (LLMs)**
- **FFmpeg** – Audio preprocessing
- **Flask** – Backend / API

---

## ⚙️ How It Works

1. User uploads a meeting audio file  
2. Audio is validated and split if it exceeds size limits  
3. Whisper converts audio into text  
4. Transcribed text is sent to an LLM via Groq API  
5. The system generates a concise meeting summary  

---


## 🎥 Demo Video

[▶️ Click here to download/watch the demo video](https://github.com/Yasaswini1807/MEETING_SUMMARIZER/blob/main/MEETING_SUMMARIZER_LIVE%20DEMO.mp4)

---

## 📁 Project Structure

---

## 🔧 Installation

### 1️⃣ Clone the Repository

git clone https://github.com/Yasaswini1807/MEETING_SUMMARIZER.git
cd MEETING_SUMMARIZER

graphql
Copy code

### 2️⃣ Create Virtual Environment (Optional but Recommended)

python -m venv venv
source venv/bin/activate

shell
Copy code

### 3️⃣ Install Dependencies

pip install -r requirements.txt

shell
Copy code

### 4️⃣ Set Environment Variable

export GROQ_API_KEY="your_api_key_here"

scss
Copy code

(Windows PowerShell)

setx GROQ_API_KEY "your_api_key_here"

yaml
Copy code

---

## ▶️ Usage

python app.py

yaml
Copy code

- Upload a meeting audio file  
- Wait for transcription and summarization  
- View the generated summary  

---

## ⭐ Key Highlights

- Fully powered by **Generative AI & LLMs**
- Designed for **real-world meeting scenarios**
- Handles **long-duration audio files**
- Clean, scalable, and production-ready design
- Ideal for productivity, enterprise, and AI applications

---

## 🚧 Future Enhancements

- Speaker diarization (who spoke what)
- Multi-language transcription
- Web-based dashboard
- Action item extraction
- Integration with meeting platforms (Zoom, Google Meet)

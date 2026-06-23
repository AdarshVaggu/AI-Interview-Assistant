# AI Interview Assistant

An AI-powered voice interview assistant that conducts conversational technical interviews and provides automated feedback.

## Features

* Voice-based interview interaction
* Real-time AI-generated follow-up questions
* Context-aware conversation memory
* Streaming text-to-speech responses using Murf AI
* Speech-to-text transcription using AssemblyAI
* Interview scoring and feedback generation
* Supports multiple interview domains and subjects

## Tech Stack

### Backend

* Flask
* LangChain
* LangGraph
* Gemini 2.5 Flash
* AssemblyAI
* Murf AI

### Frontend

* HTML
* JavaScript
* Tailwind CSS

## Setup

Create a `.env` file inside the backend folder:

```env
GOOGLE_API_KEY=YOUR_KEY
MURF_API_KEY=YOUR_KEY
ASSEMBLYAI_API_KEY=YOUR_KEY
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run backend:

```bash
python backend/app.py
```

Run frontend using Live Server.

## Future Improvements

* Resume-based interview generation
* AI-powered behavioral interviews
* Detailed analytics dashboard
* Interview history tracking
* Multi-language support

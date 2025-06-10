# AI-Companion

A personalized, voice-first conversational AI designed to be a supportive companion, mentor, and friend. This project uses a hybrid architecture, combining the power of a cloud-based LLM with high-quality, locally-run models for audio processing to ensure privacy, speed, and zero cost for STT/TTS.

## Core Technology Stack

*   **"The Brain" (LLM):** Google Gemini 1.5 Flash (via API)
*   **Speech-to-Text (STT):** OpenAI's Whisper (running locally)
*   **Text-to-Speech (TTS):** Piper TTS (running locally)
*   **Orchestration:** A custom Python script using `asyncio` and `pyaudio`.

## Project Setup

Follow these steps to get the project running locally.

### 1. Clone the Repository
Clone this repository to your local machine.

### 2. Create and Activate Virtual Environment
From the project's root directory (`AI-Companion`), create and activate a Python virtual environment. This keeps the project's dependencies isolated.

**Create:**
```bash
python -m venv .venv
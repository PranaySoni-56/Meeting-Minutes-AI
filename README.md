# AI Meeting Minutes & Action Item Generator 🎙️🧠

An end-to-end AI system that converts **meeting audio into structured meeting minutes and actionable tasks** using modern speech recognition and large language models.

This project focuses on **real-world AI pipeline design**, combining Automatic Speech Recognition (ASR) with LLM-based summarization for practical productivity use cases.


## 📌 Problem Statement

Meeting notes and action items are often written manually, which is time-consuming and error-prone. Important decisions and tasks can be missed.

**Goal:**
Automatically extract accurate meeting minutes and clear action items directly from raw audio recordings.


## 🚀 Solution Overview

This tool processes meeting audio in multiple stages:

1. Transcribes spoken audio into text
2. Summarizes discussions
3. Extracts clear, structured action items

The result is a **readable, usable meeting summary** that teams can rely on.


## 🧠 Architecture / Workflow

**Audio Input → Speech-to-Text → LLM Processing → Structured Output**

* Audio preprocessing
* Automatic Speech Recognition (ASR)
* Prompt-driven summarization
* Action item extraction

Designed with modular steps to allow easy extension or model replacement.


## 🛠️ Tech Stack

* **LLM:** Meta-Llama-3.2-3B-Instruct (closed-source usage)
* **Speech-to-Text:** OpenAI Whisper (whisper-medium.en)
* **Framework:** Hugging Face Transformers
* **Pipeline:** automatic-speech-recognition
* **Language:** Python



## ✨ Key Features

* Converts raw meeting audio into clean text
* Generates concise meeting summaries
* Extracts actionable tasks automatically
* Structured, readable output
* Designed for real-world usability


## 📂 Project Structure

* Notebook for end-to-end execution
* Sample audio files for testing
* Output folder for generated summaries
* Requirements file for reproducibility


## 🎯 What This Project Demonstrates

* Practical integration of **ASR + LLMs**
* Prompt engineering for structured outputs
* End-to-end AI pipeline design
* Applied NLP beyond toy examples
* Strong foundation for production-grade AI systems


## 🔮 Future Improvements

* Speaker diarization
* Timestamped action items
* Multi-language support
* UI interface (gardio)


## 📬 Feedback & Contributions

Feedback, suggestions, and improvements are welcome.
Feel free to open an issue or connect with me on LinkedIn.

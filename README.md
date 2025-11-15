🎙️ Text-to-Speech + DocuCast + Creative Script Generator
AI-powered Audio Narration + Smart Summarization + Creative Voiceover Generation

DocuCast transforms your boring documents into engaging, podcast-style audio files, and now includes a creative script generation pipeline powered by Gemini API — perfect for turning documents into story-like, conversational summaries with hooks, emotion, and narration cues.

🚀 Features
📑 PDF Upload

Upload any PDF — textbooks, research papers, notes, reports.

📝 Text Extraction

Extracts clean text from the entire PDF using PyMuPDF.

🤖 Smart Summarization

Summarizes large documents using facebook/bart-large-cnn from Hugging Face.

🧠 NEW — Creative Script Creator (Gemini AI)

🔥 Adds an optional creative mode that converts the summary into a narrative-style script, including:

Hooks

Storytelling flow

Micro-examples

Conversational tone

Light humor

Engaging pacing

Scene cues

Voice style tags

This turns any boring document into a fun, podcast-like explanation.

🎤 Dual-Voice Audio Generation

Splits the script into two parts and generates natural-sounding audio using two different ElevenLabs voices.

🎧 Podcast-Style Audio Merge

Combines both audio clips into a seamless MP3 using Pydub, giving a dialogue-style or host + narrator vibe.

🔊 Instant Playback

Play the final audio directly in Google Colab or download it as a finished podcast.

🛠️ Tech Stack

Python 3.x

Google Colab

PyMuPDF → PDF text extraction

Transformers (facebook/bart-large-cnn) → Summarization

Gemini API → Creative narration script generation

ElevenLabs API → Realistic TTS

Pydub + FFmpeg → Audio processing

Requests / JSON → API communication

🔧 Installation & Requirements
pip install pymupdf transformers requests pydub
apt-get install ffmpeg

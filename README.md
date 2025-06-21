# Text-to-speech-
# DocuCast 🎙️📄

Transform any PDF document into a summarized, podcast-style audio file using AI-powered summarization and realistic text-to-speech synthesis (ElevenLabs API).

---

## 🚀 Features

- 📑 **PDF Upload**: Upload any PDF document.
- 📝 **Text Extraction**: Extracts all textual content from the PDF.
- 🤖 **AI Summarization**: Uses `facebook/bart-large-cnn` transformer to summarize large documents.
- 🎤 **Dual Voice Audio**: Splits the summary into two parts and generates audio in two different voices via **ElevenLabs Text-to-Speech API**.
- 🔊 **Audio Merging**: Combines both audio clips into a seamless podcast-like MP3 file.
- 🎧 **Audio Playback**: Direct playback in Google Colab or download final podcast.

---

## 🛠️ Tech Stack

- Python 3.x
- Google Colab (for running the notebook)
- [PyMuPDF](https://pymupdf.readthedocs.io/en/latest/) (for PDF text extraction)
- [Transformers (Hugging Face)](https://huggingface.co/docs/transformers/index) (`facebook/bart-large-cnn` for summarization)
- [Pydub](https://github.com/jiaaro/pydub) (for audio processing)
- [ElevenLabs API](https://api.elevenlabs.io/) (for realistic voice synthesis)
- FFmpeg (required by Pydub)

---

## 🔧 Installation & Requirements

Before running the notebook:

```bash
pip install pymupdf transformers requests pydub
apt-get install ffmpeg

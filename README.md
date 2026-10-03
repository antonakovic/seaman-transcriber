# ⚓ Seaman Transcriber

**Seaman Transcriber** is a simple offline desktop application for converting audio and video files into text using OpenAI's Whisper speech recognition models.

The application was designed with a simple goal: select a file, start the transcription, and receive the result as a text file — without requiring Python, command-line tools, or an Internet connection.

## ✨ Features

- 🎙️ Audio and video transcription
- 🇬🇷 Greek speech recognition
- 🌍 Automatic language detection
- 📴 Fully offline transcription
- 🔒 Audio files remain on the local computer
- ⏱️ Timestamped transcription
- 📊 Real-time transcription progress
- 📁 Custom output folder selection
- 💾 Automatic `.txt` output
- 🪟 Portable Windows application
- 🚫 No Python installation required

## 📂 Supported formats

Seaman Transcriber currently supports:

`MP3` · `WAV` · `M4A` · `AAC` · `FLAC` · `OGG` · `MP4`

## 🚀 How to use

1. Download the latest portable version of **Seaman Transcriber**.
2. Extract the downloaded archive.
3. Open the `SeamanTranscriber` folder.
4. Run `SeamanTranscriber.exe`.
5. Select an audio or video file.
6. Select the folder where you want the transcription to be saved.
7. Start the transcription.

The generated transcription will be saved as a `.txt` file.

## 🧠 Speech recognition

Seaman Transcriber uses **faster-whisper** and the **Whisper large-v2** model.

The model is included with the portable distribution, allowing transcription to run locally without downloading the model when the application starts.

## 🔐 Privacy

Transcription is performed locally on the user's computer.

Audio/video files do not need to be uploaded to an external transcription service, and an active Internet connection is not required for transcription.

## 💻 Platform

Currently built and tested for:

**Windows 10 / Windows 11 — 64-bit**

## 📦 Portable version

The portable release contains the application, its required runtime files, and the speech-recognition model.

No installation of Python, VS Code, Whisper, or additional Python packages is required.

> Keep all files and folders included with `SeamanTranscriber.exe` together. Do not move the `.exe` outside its application folder.

## 🛠️ Built with

- Python
- Tkinter
- faster-whisper
- CTranslate2
- PyInstaller
- Whisper large-v2

## 📌 Project status

**Version 1.0 — Initial release**

The application is under active development.

---

### ⚓ Seaman Transcriber

A lightweight interface for local, private and offline speech-to-text transcription.

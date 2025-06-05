# Voice Based Authentication

## ✅ Prerequisites

Make sure you have the following installed:

### 🧰 System Requirements
- Python 3.7 or higher
- pip (Python package installer)
- Jupyter Notebook or JupyterLab

### 📦 Required Python Libraries

Install the following libraries using pip:

```bash
pip install SpeechRecognition pyaudio numpy scikit-learn
```

> 🔧 Note:
> - On some systems, you may need to install `portaudio` first before installing `pyaudio`.
> - You can install Jupyter using: `pip install notebook`


## 🔐 Overview
A simple Python-based system to authenticate users using their voice. It matches a user's voice input against a saved voice profile.

## 📋 Features
- Voice recording
- Audio comparison using MFCCs or simple similarity checks
- Basic CLI interface

## 🚀 How to Run
1. Run the notebook:  
   Open `voice based authentication.ipynb` in Jupyter.
2. Record your voice when prompted.
3. The system compares it to a stored voice file.

## 📦 Dependencies
- SpeechRecognition
- PyAudio
- Numpy
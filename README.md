# Medical-AI-Chatbot


## Project Overview

The Medical AI Chatbot is an advanced conversational assistant that leverages vision and audio capabilities to provide medical-related information. It integrates Large Language Models (LLM) through the Groq API, speech synthesis using gTTS/Elevenlabs, and a user-friendly interface built with Gradio.

## Features

1. **Conversational AI:** Utilizes Groq API for intelligent and context-aware medical dialogue.

2. **Vision Capabilities:** Processes and analyzes medical images for insights.

3. **Text-to-Speech:** Converts chatbot responses to speech using gTTS or Elevenlabs.

4. **User Interface:** Built using Gradio for an interactive and intuitive experience.

## Tech Stack

1. **Groq API:** For advanced language model capabilities.

2. **gTTS/Elevenlabs:** For text-to-speech conversion.

3. **Gradio:** For building the user interface.

4. **Python:** Core programming language.

## Prerequisites

- Ensure you have the following installed on your system:

- Python (>=3.8)

- Virtual environment (optional but recommended)

## Table of Contents

1. [Installing FFmpeg and PortAudio](#installing-ffmpeg-and-portaudio)
   - [macOS](#macos)
   - [Linux](#linux)
   - [Windows](#windows)
2. [Setting Up a Python Virtual Environment](#setting-up-a-python-virtual-environment)
   - [Using Pipenv](#using-pipenv)
   - [Using pip and venv](#using-pip-and-venv)
   - [Using Conda](#using-conda)
3. [Running the application](#project-phases-and-python-commands)


## Installing FFmpeg and PortAudio

### macOS

1. **Install Homebrew** (if not already installed):

   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. **Install FFmpeg and PortAudio:**

   ```bash
   brew install ffmpeg portaudio
   ```


### Linux
For Debian-based distributions (e.g., Ubuntu):

1. **Update the package list**

```
sudo apt update
```

2. **Install FFmpeg and PortAudio:**
```
sudo apt install ffmpeg portaudio19-dev
```

### Windows

#### Download FFmpeg:
1. Visit the official FFmpeg download page: [FFmpeg Downloads](https://ffmpeg.org/download.html)
2. Navigate to the Windows builds section and download the latest static build.

#### Extract and Set Up FFmpeg:
1. Extract the downloaded ZIP file to a folder (e.g., `C:\ffmpeg`).
2. Add the `bin` directory to your system's PATH:
   - Search for "Environment Variables" in the Start menu.
   - Click on "Edit the system environment variables."
   - In the System Properties window, click on "Environment Variables."
   - Under "System variables," select the "Path" variable and click "Edit."
   - Click "New" and add the path to the `bin` directory (e.g., `C:\ffmpeg\bin`).
   - Click "OK" to apply the changes.

#### Install PortAudio:
1. Download the PortAudio binaries from the official website: [PortAudio Downloads](http://www.portaudio.com/download.html)
2. Follow the installation instructions provided on the website.

---

## Setting Up a Python Virtual Environment

### Using Pipenv
1. **Install Pipenv (if not already installed):**  
```
pip install pipenv
```

2. **Install Dependencies with Pipenv:** 

```
pipenv install
```

3. **Activate the Virtual Environment:** 

```
pipenv shell
```

---

# Project Phases and Python Commands

## Phase 1: Brain of the doctor
```
python brain_of_the_doctor.py
```

## Phase 2: Voice of the patient
```
python voice_of_the_patient.py
```

## Phase 3: Voice of the doctor
```
python voice_of_the_doctor.py
```

## Phase 4: Setup Gradio UI
```
python gradio_app.py
```

---

## Usage

1. Upload medical images for analysis.

2. Interact with the chatbot through text or audio input.
  
3. Receive responses in both text and speech formats.

## Future Enhancements

- Improve image analysis accuracy.

- Add multilingual support.

- Integrate patient record management.

## License

This project is licensed under the APACHE 2.0

## Contributors

- Yaawar Kapadia

Feel free to contribute or raise issues in the repository!🚀💻🩺

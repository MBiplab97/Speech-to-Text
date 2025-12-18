# Whisper Transcription Project

This project demonstrates the use of OpenAI's Whisper library for audio transcription. Whisper is a general-purpose speech recognition model that can transcribe and translate audio files with high accuracy.

## Features
- Transcription of audio files into text.
- Language detection for spoken audio.
- Support for large pre-trained models (e.g., `turbo` model).
- Audio preprocessing, including padding and trimming.
- Spectrogram generation and decoding.

## Installation
To install the required libraries, run:
```bash
pip install -U openai-whisper
pip install faster-whisper
```

## Usage
The Jupyter Notebooks `whisper.ipynb` and `faster_whisper.ipynb` provide examples of:
- Loading the Whisper and Faster Whisper models.
- Transcribing audio files and printing the results.
- Detecting the language of the audio.
- Preprocessing audio for better transcription results.

### Faster Whisper
This repository also uses the [Faster Whisper](https://github.com/SYSTRAN/faster-whisper) library for efficient transcription of audio files. Faster Whisper provides a high-performance implementation of OpenAI's Whisper model, optimized for both GPU and CPU environments.

## How It Works
1. **Audio Loading**: The audio file is loaded and preprocessed to fit the model's requirements.
2. **Language Detection**: The model detects the spoken language in the audio.
3. **Transcription**: The audio is transcribed into text using the Whisper model.
4. **Spectrogram Analysis**: Log-Mel spectrograms are generated for audio analysis.

## References
- For more details on Whisper, visit the official [OpenAI Whisper GitHub repository](https://github.com/openai/whisper).
- For more details on Faster Whisper, visit the official [Faster Whisper GitHub repository](https://github.com/SYSTRAN/faster-whisper).
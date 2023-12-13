# Schrödinger's Cat Transcription

## Author
Mohammad Ghadban

## Overview
This Python script downloads a YouTube video, extracts the audio, and performs speech transcription using the Google Speech Recognition API. The transcription is then processed, and a Word Cloud is generated to visualize the most frequent words.

## Prerequisites
- Python
- Libraries: numpy, librosa, matplotlib, seaborn, os, scipy, youtube_dl, IPython, speech_recognition, glob, wordcloud

## Instructions
1. Run the script by providing a YouTube link when prompted.
2. The script will download the video as an mp3 file and convert it to a mono, 8000 Hz WAV file.
3. Tempo of the file is adjusted for better transcription.
4. The audio file is split into chunks of 10 seconds each.
5. Speech recognition is performed on each chunk, and the transcriptions are stored in a text file (`Schröders-cat.txt`).
6. The script then generates a Word Cloud to visualize the most common words in the transcriptions.

## Notes
- Ensure ffmpeg is installed for audio processing.
- The transcription language can be changed by modifying the `language` parameter in the script.
- The resulting Word Cloud is displayed using matplotlib.

## Usage
```bash
python script.py

# Sound Pollution Detection 🎤🔊

## Introduction 🚀

The Sound Pollution Detection project focuses on monitoring and detecting sound intensity levels in both live and recorded audio environments. The project consists of two main files, one for live sound recording (`live_sound_recording.py`) and the other for analyzing recorded audio (`analyze_recorded_audio.py`).

## Live Sound Recording (`live_sound_recording.py`) 🎙️

This file utilizes libraries such as `sounddevice` for real-time audio capture, `numpy` for numerical operations, and `soundfile` for saving the recorded audio. The live sound recording module helps in monitoring sound intensity levels as they occur.

### Prerequisites 📋

Make sure you have the required libraries installed:

```bash
pip install sounddevice numpy soundfile
```

### How to Run ▶️

1. Execute the following command:

```bash
python live_sound_recording.py
```

2. The live sound recording module will start capturing real-time audio data.

## Analyze Recorded Audio (`analyze_recorded_audio.py`) 🎶

This file is designed to analyze pre-recorded audio files to detect sound pollution levels. It leverages the same libraries (`numpy` and `soundfile`) for numerical operations and audio file processing.

### Prerequisites 📋

Ensure the necessary libraries are installed:

```bash
pip install numpy soundfile
```

### How to Run ▶️

1. Provide the path to the recorded audio file within the script.

2. Execute the following command:

```bash
python analyze_recorded_audio.py
```

3. The script will process the audio file and provide insights into sound pollution levels.


# Voice LLM Chat

## Setup

Run
```
./setup.bash
```

## Usage

```
.
├── setup.bash 		Sets up the environment (apt, venv/pip)
├── tools.py
├── recorder.py 	Records from microphone to audio.wav
├── audio.wav
├── transcribe.py	Transcribes audio.wav file to transcription.txt
├── transcription.txt
├── invoke.py 		Queries LLM using transcription.txt and gets response.txt
├── response.txt
├── text2wav.py		Converts response.txt to response.wav
└── response.wav
```

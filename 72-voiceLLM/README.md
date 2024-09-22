# Voice LLM Chat

## Setup

Run
```
./setup.bash
```

## Usage

```
.
├── setup.bash 			Sets up the environment (apt, venv/pip)
├── tools.py			Tools
│
├── recorder.py 		Records from microphone to audio.wav
├── audio.wav			Recorded audio
│
├── speech2text_api.py		Speech recognition audio.wav->transcription.txt with WhisperAI API
├── speech2text_whisperai.py	Speech recognition audio.wav->transcription.txt with WhisperAI locally
├── transcription.txt 		Transcription
│
├── invoke.py			Queries LLM using transcription.txt and gets response.txt using DeepInfra API
├── response.txt		LLM Query result
│
├── synth-11Labs.py		response.txt->response.wav with ElevenLabs API
├── synth-TTS.py		response.txt->response.wav with Amazon TTS locally
└── response.wav		response audio
```

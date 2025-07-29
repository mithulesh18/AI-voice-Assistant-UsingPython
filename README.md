
# AI Voice Assistant using Python

## Description
A Python-based voice assistant capable of recognizing speech, responding with synthesized voice, and performing tasks such as web search, time greeting, and more.

## Features
- Speech recognition using `speech_recognition`
- Text-to-speech using `pyttsx3`
- Basic command processing (Wikipedia, browser opening)
- Modular and expandable structure

## Requirements
- Python 3.x
- speechrecognition
- pyttsx3
- pyaudio (for microphone access)

## Accuracy Notes
The accuracy of voice recognition depends on the `recognize_google` method used from the SpeechRecognition library, which generally has 85-95% accuracy in clear conditions.

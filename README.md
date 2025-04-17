# VIRA - Voice Interactive Response Assistant

VIRA (Voice Interactive Response Assistant) is a smart desktop assistant built using C++ and Python. It listens to your voice commands, responds using text-to-speech, plays songs from YouTube and opens websites.

---

## Features

- Listens to your voice commands using speech recognition  
- Responds with natural-sounding text-to-speech  
- Opens websites like Google, YouTube, Facebook, and LinkedIn  
- Plays popular songs on YouTube through voice commands  
- Runs continuously until you say “exit” or Type "N" 

---

## Tech Stack

- C++ – Main logic and system integration  
- Python – Voice input handling using Google API Speech-to-Text  
- espeak – Text-to-speech  
- speech_recognition – Python speech recognition module  
- YouTube URLs – For song playback

---

## Project Structure

```bash
VIRA/
├── main.cpp               # C++ main assistant logic
├── voice_test.py          # Python script for capturing voice and saving to file
├── command.txt            # File where the voice command is stored
├── tempCodeRunnerFile.cpp # Temporary CPP Code running file
├── README.md              # Project documentation

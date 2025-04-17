# VIRA-Voice-Interactive-Response-Assistant-
VIRA – A Voice Interactive Response Assistant built with C++ and Python that listens, talks, plays songs and opens websites.
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
├── main.cpp                # C++ main assistant logic
├── voice_test.py          # Python script for capturing voice and saving to file
├── show_vira_ui.py        # Python script to display the AI image
├── command.txt            # File where the voice command is stored
├── vira_ui.png            # Image shown as the AI face
├── README.md              # Project documentation

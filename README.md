This project is a voice-activated notetaking application that uses Python to listen for commands, recognize speech, and write notes to text files. It integrates speech recognition for command parsing and text-to-speech (TTS) for interaction. The system listens for a specific activation word and responds to voice commands to log notes with timestamps.

Key Components:
Speech Recognition: Uses the speech_recognition library to capture and convert spoken commands into text.
Text-to-Speech (TTS): Uses the pyttsx3 library to provide verbal feedback and notifications.
Voice Activation: The system responds to a specific activation word ('computer') to start listening for commands.
Note Logging: Records notes with a timestamp in text files.

Features:
Voice Command Parsing: Detects and processes voice commands.
Text-to-Speech Feedback: Provides audible feedback for interactions.
Note Recording: Saves spoken notes to text files with timestamps

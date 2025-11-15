G-One is a voice-controlled AI personal assistant built using Python, capable of performing day-to-day automation tasks such as opening websites, fetching information, reporting time, and more through speech recognition and text-to-speech interactions.

This project demonstrates speech processing, automation, and API integration in Python — simulating a basic version of an intelligent voice assistant like Alexa or Siri.

 Features

 Voice Interaction: Understands user speech via speech_recognition and responds using pyttsx3.

 Web Automation: Opens common websites such as YouTube, Google, Gmail, and Stack Overflow.

 News Headlines: Fetches top headlines from Times of India.

 Time Functionality: Announces the current system time.

Conversational Responses: Answers questions like "Who are you?" or "Who made you?".

 System Commands: Supports system log off/sign-out actions via command linee.

🧩 Technologies Used

Python 3.x

speech_recognition → Converts spoken input to text

pyttsx3 → Converts text to speech

webbrowser → Opens websites and URLs

datetime → Handles time-based responses

subprocess → Executes system commands

requests → For potential API calls

Project Structure


How to Run

Install dependencies:

pip install speechrecognition pyttsx3 requests

Run the script:

python main.py


Speak your command:
Example:

“Open YouTube”

“What’s the time?”

“Who are you?”

“Goodbye” (to exit)

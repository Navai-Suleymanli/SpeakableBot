Bella Bot - Personal Assistant
Overview
Bella Bot is a personal voice assistant designed to interact with users using speech recognition and voice synthesis. It responds to various commands such as performing web searches, opening websites, playing music, and providing time and information. Bella Bot is built using Python and integrates several key libraries to handle voice interaction, web automation, and simple task management.

Features
Voice recognition using speech_recognition to take user commands.
Text-to-speech responses using pyttsx3 and gTTS.
Can fetch information from Wikipedia and respond with a summary.
Opens websites like YouTube, Google, Gmail, and others.
Plays music from a designated folder.
Provides the current time and greets the user based on the time of day.
Responds to casual conversations and questions.
Can execute system commands like opening Notepad and VS Code.
Requirements
Python 3.x
Required libraries:
pyttsx3
speech_recognition
wikipedia
webbrowser
os
smtplib
gtts
tkinter
PIL (Pillow)
subprocess
playsound
To install these dependencies, you can run the following commands:

bash
Kodu kopyala
pip install pyttsx3 SpeechRecognition wikipedia gtts playsound Pillow
How It Works
1. Greeting the User
Bella Bot welcomes the user based on the time of the day (morning, afternoon, evening). It uses the datetime module to get the current hour and tailors the greeting accordingly.

2. Voice Commands
The assistant listens for commands through the microphone using the speech_recognition library. Once a command is captured, it is processed, and the assistant performs the corresponding task.
Example commands:
"Open YouTube" — Opens YouTube in the browser.
"Play music" — Plays a song from the specified music directory.
"What's the time?" — Responds with the current time.
3. Task Execution
If a command includes "Wikipedia," Bella Bot searches Wikipedia for the requested topic and reads a short summary.
Commands like "open Google" or "open Gmail" will open the respective websites in the default browser.
If a user asks to open applications like Notepad or Visual Studio Code, Bella Bot will locate and launch them.
4. Casual Conversation
Bella Bot can respond to casual conversation or questions like:

"Who are you?" — Introduces itself as Bella Bot.
"Do you love me?" — Responds affectionately.
"Who made you?" — Credits its creators.
"Tell me something" — Compliments the user.
5. User Interaction
Bella Bot uses gTTS and pyttsx3 for speech synthesis, allowing it to speak responses aloud. This enhances user interaction by providing an auditory feedback loop.

6. Additional Features
Bella Bot can help users with information about a website (like "Bellachefo") and how to use it.
It can also provide recommendations or facts, such as "Who is the best chef in the world?"
The bot also handles humorous responses like "Shut up" or "Go away."
7. Exiting the Program
The bot can be gracefully exited by saying "Bye," upon which it responds with a farewell and terminates the program.

How to Use
Run the script in a Python environment.
Bella Bot will greet you and prompt for your name.
Once initialized, Bella Bot will continuously listen for voice commands.
Speak commands such as:
"Open YouTube"
"Play music"
"What's the time?"
To stop Bella Bot, say "Bye."
Future Improvements
Add more functionality for controlling additional applications and automating tasks.
Enhance conversation abilities with natural language processing (NLP) techniques.
Introduce custom voice settings or allow for different accents and languages.
Allow more robust error handling for commands not recognized.
License
This project is open-source and free to use. You are welcome to modify and extend the code for personal use or contribute to its development.

By Khatai and Navai, creators of Bella Bot!

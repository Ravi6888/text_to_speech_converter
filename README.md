## text_to_speech_converter

Text to Speech Converter

A simple Python GUI application that converts user-entered text into speech using the Google Text-to-Speech (gTTS) API.

The program provides an easy-to-use interface built with Tkinter and plays the generated audio instantly.

________________________________________

	**Features**

•	 Convert text entered by the user into speech.

•	 Automatically play the generated speech file.

•	 Reset or clear the input text field.

•	 Exit the application easily with one click.

•	 GUI built with Tkinter for ease of use — no command line required.

________________________________________

	**Tech Stack**

Component	Description

Language	Python 3.x

GUI Library	Tkinter (built-in)

Text-to-Speech	gTTS (Google Text-to-Speech API)

Audio Playback	playsound / OS default player

Operating System	Works on Windows, macOS, and Linux

________________________________________

	**Installation and Setup**

1. Clone the Repository

  git clone https://github.com/Ravi6888/text_to_speech_converter.git

  cd text_to_speech_converter

2. Install Required Packages

  Make sure you have Python 3 installed. Then install dependencies:

pip install gTTS playsound 

3. Run the Application

  python text_to_speech_converter.py

________________________________________

	**How It Works**

1.	Launch the app — a Tkinter window appears.

2.	Enter any text into the input field.

3.	Click PLAY to:

  •	Convert the text into speech using gTTS.
  
  •	Save it locally as GetProjects.mp3.
  
  •	Play it automatically.


5.	Click RESET to clear the text field.

6.	Click EXIT to close the app.

________________________________________

	**GUI Preview** 
 
<img width="293" height="278" alt="image" src="https://github.com/user-attachments/assets/eccc2d41-7a72-44f4-a3db-ce9978308c95" />

________________________________________

	**Example**

Enter Text: Hello, welcome to the Text to Speech Converter!

[Click PLAY]

--> Application creates "GetProjects.mp3"

--> Audio plays automatically

________________________________________

	**File Details**

File	Description

text_to_speech_converter.py	------------ Main script that creates the GUI and handles text-to-speech conversion

GetProjects.mp3	  ------------------Temporary output audio file generated when you click PLAY

________________________________________

	**Customization Ideas**

•	Allow saving audio with custom filenames.

•	Add language selection (e.g., English, French, Hindi).

•	Add voice speed and tone adjustments.

•	Support file input (convert .txt file to speech).

•	Integrate with a microphone for live reading.


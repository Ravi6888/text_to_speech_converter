<h1 align="center">Text to Speech Converter</h1>

<p align="center">
  <b>A simple Python GUI application that converts text to speech using Google Text-to-Speech (gTTS)</b><br>
  Built with <b>Tkinter</b> for the interface and <b>playsound</b> for instant audio playback.
</p>

<hr>

<h2>➤ Project Overview</h2>
<p>
This project is a simple Python GUI-based <b>Text to Speech Converter</b> that allows users to type or paste any text and instantly hear it spoken aloud.<br>
It uses the <b>Google Text-to-Speech (gTTS)</b> API to generate the audio and plays it automatically using <b>playsound</b> or the system’s default audio player.<br>
The application interface is built with <b>Tkinter</b> for ease of use — no command line required.
</p>

<hr>

<h2>➤ Features</h2>
<ul>
  <li> Convert user-entered text into speech instantly.</li>
  <li> Automatically play the generated audio file.</li>
  <li> Reset or clear the input text field.</li>
  <li> Exit the application with one click.</li>
  <li> Simple GUI built with Tkinter — beginner-friendly and cross-platform.</li>
</ul>

<hr>

<h2>➤ Tech Stack</h2>
<table>
<tr><th>Component</th><th>Description</th></tr>
<tr><td><b>Language</b></td><td>Python 3.x</td></tr>
<tr><td><b>GUI Library</b></td><td>Tkinter (built-in)</td></tr>
<tr><td><b>Text-to-Speech</b></td><td>gTTS (Google Text-to-Speech API)</td></tr>
<tr><td><b>Audio Playback</b></td><td>playsound / OS default player</td></tr>
<tr><td><b>Operating System</b></td><td>Windows, macOS, Linux</td></tr>
</table>

<hr>

<h2>➤ Installation and Setup</h2>

<ol>
  <li><b>Clone the Repository</b>
    <pre>
git clone https://github.com/Ravi6888/text_to_speech_converter.git
cd text_to_speech_converter
    </pre>
  </li>

  <li><b>Install Required Packages</b>
    <p>Make sure you have Python 3 installed, then install dependencies:</p>
    <pre>
pip install gTTS playsound
    </pre>
  </li>

  <li><b>Run the Application</b>
    <pre>
python text_to_speech_converter.py
    </pre>
  </li>
</ol>

<hr>

<h2>➤ How It Works</h2>
<ul>
  <li> Launch the application — a Tkinter window appears.</li>
  <li> Enter any text into the input field.</li>
  <li> Click <b>PLAY</b> to:
    <ul>
      <li>Convert the text into speech using <b>gTTS</b>.</li>
      <li>Save it locally as <code>GetProjects.mp3</code>.</li>
      <li>Play it automatically.</li>
    </ul>
  </li>
  <li> Click <b>RESET</b> to clear the input field.</li>
  <li> Click <b>EXIT</b> to close the app.</li>
</ul>

<hr>

<h2>➤ GUI Preview</h2>
<p align="center"><i><img width="354" height="336" alt="Screenshot 2025-10-31 172804" src="https://github.com/user-attachments/assets/2007eeb8-5c01-49ac-a675-54abab2f1104" />
</i></p>

<hr>

<h2>➤ Example</h2>
<p><b>Enter Text:</b> Hello, welcome to the Text to Speech Converter!</p>
<p><b>[Click PLAY]</b></p>
<pre>
--> Application creates "GetProjects.mp3"
--> Audio plays automatically
</pre>

<hr>

<h2>➤ File Details</h2>
<table>
<tr><th>File</th><th>Description</th></tr>
<tr><td>text_to_speech_converter.py</td><td>Main script that creates the GUI and handles text-to-speech conversion.</td></tr>
<tr><td>GetProjects.mp3</td><td>Temporary output audio file generated when you click PLAY.</td></tr>
</table>

<hr>

<h2>➤ Customization Ideas</h2>
<ul>
  <li> Allow saving audio files with custom filenames.</li>
  <li> Add language selection (e.g., English, French, Hindi).</li>
  <li> Add voice speed and tone adjustment options.</li>
  <li> Support importing a text file (.txt) to convert it to speech.</li>
  <li> Integrate a microphone feature for live reading.</li>
</ul>

<hr>



<hr>

<p align="center">
⭐ <i>If you found this project useful, consider giving it a star!</i> ⭐
</p>

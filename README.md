Language Translator Application
Description
This project is a Speech-to-Speech Language Translator built using Python. It enables users to record audio, transcribe it to text, translate the text into a target language, and play the translated text as audio. The application provides a simple interface for multilingual translation and supports playback of the translated speech.

Features
Speech-to-Text: Converts recorded audio into text using the Faster Whisper model.
Text Translation: Translates the transcribed text into the selected target language using the Groq API.
Text-to-Speech: Converts the translated text into audio using gTTS.
Multilingual Support: Supports multiple languages for translation, including Portuguese, Spanish, German, French, Italian, and more.
User-Friendly Interface: Built with Streamlit for an easy-to-use web interface.
Tech Stack
Python: Programming language.
Streamlit: For the user interface.
Faster Whisper: For speech-to-text transcription.
Groq API: For text translation.
gTTS: For text-to-speech audio conversion.
Decouple: For managing environment variables.
Installation
Prerequisites
Python 3.9 or later installed.
Groq API key.
Required Python libraries (see requirements.txt).

Usage
Open the Streamlit app in your browser. It will typically run at http://localhost:8501.
Enter your Groq API key in the input field.
Record audio using the provided audio recorder.
Select the target language for translation.
View the transcribed text, translated text, and listen to the translated speech.
Supported Languages
Portuguese (pt)
Spanish (es)
German (de)
French (fr)
Italian (it)
Dutch (nl)
Russian (ru)
Japanese (ja)
Chinese (zh)
Korean (ko)

About Me
Hi, I am Amritanshu Bhardwaj, a 3rd-year student at BMS College of Engineering, pursuing a B.E. in Artificial Intelligence and Data Science. I am passionate about building AI-driven applications and exploring the potential of natural language processing and machine learning to solve real-world problems. This project reflects my interest in creating innovative tools that bridge the gap between technology and language.

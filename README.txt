This is a real-time voice-based AI agent that:

* Takes speech input from microphone
* Converts speech → text
* Uses OpenAI to generate response
* Converts response → speech and plays it

---

Features

* Real-time speech recognition
* AI reasoning (chain-of-thought)
* Tool usage (weather + system commands)
* Text-to-speech output

---

Tech Stack

* Python
* OpenAI API
* SpeechRecognition
* Async TTS

---
Setup Instructions

 1. Clone repo

git clone https://github.com/YOUR_USERNAME/voice-agent.git
cd voice-agent

---

 2. Create virtual environment

python -m venv venv
venv\Scripts\activate

---
 3. Install dependencies

pip install -r requirements.txt

---
4. Add API key

Create `.env` file:

OPENAI_API_KEY=your_key

---

 5. Run

python main.py

---

🎤 Usage

Speak into microphone and the AI will respond with voice.

---

 Notes

* Works only on local machine (requires microphone & speaker)
* Not deployable on cloud due to hardware dependencies
* Requires internet for OpenAI API

---
Future Improvements

* Web-based UI
* Browser voice support
* Full deployment

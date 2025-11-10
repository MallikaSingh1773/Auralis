# Auralis – Personal AI Voice Assistant

Auralis is a personal AI voice assistant that listens to commands, understands user intent, and performs actions in real time. It is built using Python, Flask, speech recognition, and LLM-based intent processing.

## Features

* Real-time speech recognition
* Intent understanding using LLM
* Executes system-level actions
* Flask backend with a simple frontend UI
* Modular and easy to extend

## Tech Stack

### Backend

* Python
* Flask
* SpeechRecognition and PyAudio
* OpenAI / LLM integration

### Frontend

* HTML
* CSS
* JavaScript

## Project Structure

```
Auralis/
├── backend/
│   ├── auth/
│   ├── (API and intent logic)
│
├── frontend/
│   ├── index.html
│   ├── script.js
│
├── main.py
├── run.py
└── README.md
```

## How to Run

### 1. Clone the repository

git clone [https://github.com/MallikaSingh1773/Auralis.git](https://github.com/MallikaSingh1773/Auralis.git)
cd Auralis

### 2. Install dependencies

pip install -r requirements.txt

### 3. Run the backend

python run.py

### 4. Open the app

Open the browser and go to:
[http://localhost:5000](http://localhost:5000)

## How Auralis Works

Voice → Speech to Text → Intent Detection → Action → Response

1. User speaks
2. Auralis converts speech to text
3. LLM detects the user’s intent
4. Backend performs the action
5. Response is shown in the UI

## Future Enhancements

* Improve speech accuracy (Whisper)
* Add RAG-based knowledge responses
* Add more voice commands
* Build a dashboard UI
* Add mobile support

## Contributing

Pull requests and suggestions are welcome.

## License

This project is licensed under the MIT License.

---

Bas ab **exactly perfect GitHub structure tree** dikhega.
Agar chaho toh main isme **badges, logo, or screenshot section** bhi add kar dungi!

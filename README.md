Auralis – Your Personal AI Voice Assistant

Auralis is a lightweight, extensible AI voice assistant built using Python, Flask, speech recognition, and LLM-based intent handling. It listens to voice commands, understands the user’s intent, and performs actions in real time — just like a mini Jarvis.

🚀 Features

🎙 Real-time Speech Recognition
Converts voice to text with high accuracy.

🧠 Intent Understanding using LLM
Detects what the user wants (open apps, search, respond, etc.).

⚙️ Action Execution
Performs system operations based on user commands.

🔁 Interactive Backend + Frontend Sync
Flask backend + clean frontend interface.

🗂 Modular Code Structure
Easy to expand with new features or custom commands.

🛠 Tech Stack

Backend:

Python

Flask

SpeechRecognition

PyAudio

LLM integration (OpenAI / custom model)

Frontend:

HTML/CSS/JS

Simple clean UI for displaying responses

📂 Project Structure
Auralis/
│
├── backend/
│   ├── auth/
│   ├── ... (API & processing)
│
├── frontend/
│   ├── index.html
│   ├── scripts.js
│
├── main.py
├── run.py
└── README.md

▶️ How to Run the Project
1. Clone the Repo
git clone https://github.com/MallikaSingh1773/Auralis.git
cd Auralis

2. Install Dependencies
pip install -r requirements.txt

3. Start the Backend
python run.py

4. Open the Frontend

Go to:

http://localhost:5000

🧩 How It Works (Pipeline)

Voice → Text → Intent → Action → Response

User speaks a command

Auralis converts speech to text

LLM detects the intent

System performs the action

Response is shown on UI

🧱 Future Improvements

Add RAG-based knowledge responses

Add integration with smart devices

Web-based control panel

Emotion-aware responses

Replace speech-recognition with Whisper for accuracy

🤝 Contributing

Pull requests are welcome!
If you want to improve features or add new actions, feel free.

📄 License

This project is open-source under the MIT License.

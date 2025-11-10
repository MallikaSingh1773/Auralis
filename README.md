# Auralis – Personal AI Voice Assistant

Auralis is a personal AI voice assistant that listens to commands, understands user intent, and performs actions in real time. It is built using Python, Flask, speech recognition, and LLM-based intent processing. The goal of Auralis is to provide a lightweight “Jarvis-like” assistant that can be extended easily.

---

## 🚀 Features
- 🎙 Real-time speech recognition  
- 🧠 LLM-based intent understanding  
- ⚙️ Executes system-level actions  
- 🌐 Flask backend + simple frontend UI  
- 🛠 Modular and easy to extend  

---

## 🛠 Tech Stack
**Backend**
- Python  
- Flask  
- SpeechRecognition & PyAudio  
- OpenAI/LLM integration  

**Frontend**
- HTML, CSS, JavaScript  

---

## 📁 Project Structure
Auralis/
│
├── backend/
│ ├── auth/
│ ├── (API + intent logic)
│
├── frontend/
│ ├── index.html
│ ├── script.js
│
├── main.py
├── run.py
└── README.md


## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/MallikaSingh1773/Auralis.git
cd Auralis
2. Install dependencies
bash
Copy code
pip install -r requirements.txt
3. Run the backend
bash
Copy code
python run.py
4. Open the app
Go to:

arduino
Copy code
http://localhost:5000
🔄 How Auralis Works
Voice → Speech-to-Text → Intent Detection → Action → Response

User speaks

Auralis converts speech to text

LLM detects the user’s intent

Backend performs the required action

Response is shown in UI

📌 Future Enhancements
Better speech accuracy (Whisper)

Add RAG for contextual knowledge

Add more voice commands

Build a dashboard UI

Add mobile support

🤝 Contributing
Pull requests and suggestions are welcome.



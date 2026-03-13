
# 🧠 Jarvis AI Voice Assistant

An intelligent **AI-powered voice assistant** built with **Python** that can understand voice commands, interact with AI models, control the system, and automate tasks.
Jarvis listens for the wake word **"Jarvis"**, processes the command, and responds with natural speech.

This project combines **speech recognition, text-to-speech, and AI conversation** to create a simple but powerful personal assistant.

---

# 🚀 Features

### 🎤 Voice Interaction

* Wake word detection (**"Jarvis"**)
* Real-time voice command recognition
* Natural speech responses using TTS

### 🤖 AI Integration

* Uses **DeepSeek R1 via OpenRouter API**
* Conversational AI responses
* Responds in the **same language spoken by the user**

### 💻 System Control

Jarvis can perform tasks such as:

* Open applications (Chrome)
* Search Google
* Open folders
* Shutdown the system
* General AI conversation

### ⛔ Interruptible Speech

Users can stop Jarvis speaking by saying **"stop"**.

---

# 🛠 Tech Stack

| Technology        | Purpose                   |
| ----------------- | ------------------------- |
| Python            | Core programming language |
| SpeechRecognition | Voice input recognition   |
| Pyttsx3           | Text-to-speech engine     |
| OpenRouter API    | AI conversation model     |
| DeepSeek R1       | AI reasoning model        |
| Requests          | API communication         |
| Webbrowser        | Opening web pages         |
| Subprocess / OS   | System commands           |

---

# 📂 Project Structure

```
Jarvis-AI-Assistant
│
├── jarvis.py          # Main assistant script
├── requirements.txt   # Python dependencies
└── README.md          # Project documentation
```

---

# ⚙️ Installation

## 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/jarvis-ai-assistant.git
cd jarvis-ai-assistant
```

---

## 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

or manually install:

```bash
pip install SpeechRecognition pyttsx3 requests pyaudio
```

---

## 3️⃣ Configure API Key

Open the script and replace:

```python
API_KEY = "your-openrouter-api-key"
```

Get your key from:

[https://openrouter.ai](https://openrouter.ai)

---

## ▶️ Run Jarvis

```bash
python jarvis.py
```

Jarvis will start listening for the wake word.

Example:

```
User: Jarvis
Jarvis: Yes? What would you like me to do?
```

---

# 🎙 Example Commands

### System Commands

```
Jarvis open chrome
Jarvis shutdown
Jarvis open folder documents
```

### Web Commands

```
Jarvis search for artificial intelligence
Jarvis google machine learning roadmap
```

### AI Chat

```
Jarvis explain quantum computing
Jarvis tell me a joke
```

---

# 🔒 Security Note

Never upload your **API key** publicly to GitHub.
Use environment variables or `.env` files for production projects.

Example:

```python
import os
API_KEY = os.getenv("OPENROUTER_API_KEY")
```

---

# 🌟 Future Improvements

Planned enhancements:

* Smart home integration
* WhatsApp / Telegram automation
* Email sending capability
* Calendar and reminders
* Multi-language voice models
* GUI interface
* Local LLM support

---

# 🤝 Contributing

Contributions are welcome.

Steps:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a pull request

---

# 📜 License

This project is open-source and available under the **MIT License**.

---

# 👨‍💻 Author

**Navin**
AI / ML Engineer
Interested in **AI systems, automation, and intelligent assistants**


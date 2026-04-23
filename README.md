# 🟢 L.O.K.I — Logical Operational Kinetic Intelligence

> **REY XXXVII** — An advanced AI desktop assistant powered by Google Gemini Live API

![Python](https://img.shields.io/badge/Python-3.11+-blue?style=flat-square&logo=python)
![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square&logo=windows)
![AI](https://img.shields.io/badge/AI-Gemini%20Live-orange?style=flat-square&logo=google)

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎤 **Real-time Voice** | Live conversation via microphone with Gemini |
| 🖥️ **Screen Control** | Volume, brightness, WiFi, Bluetooth, dark mode |
| 🌐 **Browser Automation** | Open sites, search, click, fill forms (Playwright) |
| 📂 **File Management** | Create, move, copy, delete, organize files |
| 🔍 **Web Search** | DuckDuckGo-powered intelligent search |
| 🎮 **Game Updates** | Steam & Epic Games library management |
| ✈️ **Flight Finder** | Search Google Flights and compare options |
| 📺 **YouTube** | Play, summarize, and get video info |
| 💬 **Messaging** | Send WhatsApp/Telegram messages |
| ⏰ **Reminders** | Schedule reminders via Task Scheduler |
| 🧠 **Memory** | Remembers user preferences & personal info |
| 👁️ **Vision** | Screen capture & webcam analysis |
| 💻 **Code Helper** | Write, edit, explain, and run code |
| 🏗️ **Dev Agent** | Build complete multi-file projects |

---

## 🚀 Quick Start

### Prerequisites
- **Python 3.11+**
- **Windows 10/11**
- **Google Gemini API Key** ([Get one here](https://aistudio.google.com/apikey))

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/LOKI-337.git
cd LOKI-337

# 2. Run setup (installs dependencies + Playwright browsers)
python setup.py

# 3. Launch LOKI
python main.py
```

### First Run
1. **Register** with a username and password
2. **Login** with your credentials
3. **Enter your Gemini API Key** when prompted
4. **Start talking!** LOKI listens via your microphone

---

## 📁 Project Structure

```
LOKI-337-main/
├── main.py              # Entry point — Gemini Live session
├── ui.py                # Tkinter GUI with animated HUD
├── setup.py             # Dependency installer
├── requirements.txt     # Python packages
├── actions/             # Tool modules
│   ├── open_app.py
│   ├── browser_control.py
│   ├── computer_settings.py
│   ├── file_controller.py
│   ├── web_search.py
│   ├── youtube_video.py
│   ├── flight_finder.py
│   ├── game_updater.py
│   └── ...
├── agent/               # Multi-step task execution
│   ├── task_queue.py
│   ├── planner.py
│   └── executor.py
├── core/                # System prompts & auth
│   ├── prompt.txt
│   └── auth.py
├── config/              # API keys & user data
│   ├── api_keys.json
│   └── users.json
└── memory/              # Long-term user memory
    ├── memory_manager.py
    └── long_term.json
```

---

## ⚙️ Configuration

After first launch, your API key is stored in `config/api_keys.json`:

```json
{
    "gemini_api_key": "YOUR_KEY_HERE",
    "os_system": "windows"
}
```

---

## 🛡️ Security Notes

- API keys are stored **locally** and never transmitted except to Google's API
- User credentials are hashed with **SHA-256 + salt**
- `.gitignore` excludes `api_keys.json` and `users.json`

---

## 📜 License

This project is for personal/educational use.

---

**Built with ❤️ by Krishna Rana**

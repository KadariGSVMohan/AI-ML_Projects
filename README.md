


# 🎙️ Voice-Controlled Smart Assistant (Python Chatbot)

## 📌 Project Overview

This Python-based smart assistant is a **voice-enabled chatbot** that uses OpenAI's GPT model to respond to user queries in natural language. It listens to your voice commands, processes them using GPT-3.5, speaks the response aloud, and can also perform specific actions like opening websites.


## 🔧 Features

- 🎤 Converts speech to text using a microphone
- 🧠 Processes questions using OpenAI’s GPT-3.5
- 🔊 Converts text replies into speech
- 🌐 Opens web pages like YouTube, Google, or StackOverflow via voice commands
- ❌ Can exit the program on command
- 🔁 Runs in a continuous loop until the user says "exit" or "quit"

---

## 📂 Folder Structure

```

smart-assistant/
│
├── main.py                # Main Python script with logic
├── apikey.py              # Contains your API key securely
├── README.md              # Project documentation
└── requirements.txt       # All required dependencies

````

---

## 📜 Requirements

- Python 3.x
- `openai`
- `pyttsx3`
- `speechrecognition`
- `pyaudio` *(for microphone access)*
- `webbrowser` (built-in)

---

## 📥 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/smart-assistant.git
cd smart-assistant
````

2. Install the required libraries:

```bash
pip install openai pyttsx3 SpeechRecognition pyaudio
```

3. Add your API key in a separate file `apikey.py`:

```python
# apikey.py
api_data = "your-openai-api-key-here"
```

---

## 🚀 How to Use

1. Run the main script:

```bash
python main.py
```

2. Say a question or command such as:

   * "What is the capital of India?"
   * "Open YouTube"
   * "Tell me a joke"
   * "Exit"

3. The assistant will:

   * Convert your voice to text
   * Get a reply from GPT-3.5
   * Speak the response aloud
   * Perform actions if applicable

---

## 🔍 Voice Command Examples

| Command              | Action Performed            |
| -------------------- | --------------------------- |
| "Open YouTube"       | Opens YouTube in browser    |
| "Open Google"        | Opens Google in browser     |
| "Open StackOverflow" | Opens StackOverflow         |
| "What is Python?"    | Gives a spoken explanation  |
| "Exit" or "Quit"     | Ends the program gracefully |



## ⚠️ Notes

* Make sure your **microphone is working**.
* On some systems, `pyaudio` might need to be installed via:

```bash
pip install pipwin
pipwin install pyaudio
```

* Use `sapi5` voice engine for Windows. For Linux/macOS, modify `pyttsx3.init()`.



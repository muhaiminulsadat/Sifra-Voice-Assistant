# SIFRA-Voice-Assistant

SIFRA is a Python-based voice assistant that interacts with the user through speech recognition and performs tasks like opening applications, controlling system settings, searching on Google or Wikipedia, adjusting volume and brightness, scrolling, and responding using AI through Gemini API.

This project uses speech recognition and text-to-speech (TTS) to provide a hands-free assistant experience, similar to Iron Man's Jarvis.

---

## 🛠 Features

- Greet the user according to the time of day (morning, afternoon, evening)
- Recognize voice commands using Google Speech Recognition
- Speak responses using pyttsx3
- Time & Date announcements
- Wikipedia search with spoken summary
- Open websites like YouTube, Google, LinkedIn, Facebook
- Close, minimize, maximize, restore, or switch active windows
- Volume control: increase, decrease, mute
- Brightness control: increase, decrease
- Scroll up and down
- AI-powered responses using Google Gemini API
- Exit gracefully with a voice command

---

## 💻 Requirements

- Python 3.11 or higher
- Packages: `pyttsx3`, `SpeechRecognition`, `wikipedia`, `pyautogui`, `pycaw`, `comtypes`, `google-generativeai`, `screen-brightness-control`, `time`

---

## ⚙️ How to Run

1. Create a virtual environment:

   ```bash
   conda create --prefix .\sifra python=3.11 -y
   ```

2. Activate virtual environment:

   ```bash
   conda activate sifra
   ```

3. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the sifra script:

   ```bash
   python sifra.py
   ```

## 🎤 Example Voice Commands

Speak commands and interact with your voice assistant. Some examples:

- **"Wikipedia Python"**  
  → Searches Wikipedia and reads a short summary.

- **"Open YouTube"**  
  → Opens YouTube in the browser.

- **"Volume up"**  
  → Increases system volume.

- **"Brightness down"**  
  → Decreases screen brightness.

- **"Switch window"**  
  → Switches between active windows.

- **"Stop"**  
  → Exits the assistant.



## 👨‍💻 Author

**Muhaiminul Islam Sadat**

Inspired by Tony Stark's JARVIS


### 📜 License


---

If you want, I can also **create a ready-to-use `requirements.txt`** file with all your project dependencies so anyone can run your SIFRA without errors.  

Do you want me to do that next?

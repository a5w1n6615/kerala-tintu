# Tintu-AI-Assistant
<p align='center'>
  <img src = "https://github.com/JoelShine/JARVIS-AI-ASSISTANT/blob/main/jarvis-assets/J.A.R.V.I.S.png" height='300' width='300'> <!-- Swap with a fun Kerala-themed image later, e.g., a cartoon Tintu with coconut tree -->
  <br><em>Hey Aswin! Your cheeky Kerala buddy, ready to chat in Manglish. 🥥🤖</em>
</p>

A true Artificial Intelligent Assistant with ALICE as backend, offline speech recognition via Vosk, and gTTS for natural Malayalam/Manglish text-to-speech. Inspired by Iron Man's J.A.R.V.I.S., but with a desi twist—built for Kerala vibes!

Unlike other assistants, this **Tintu** is a bilingual AI powerhouse: handles Manglish commands (Romanized Malayalam + English) like "Tintu joke paray" or "Kochi weather check cheyyu," responds in a fun mix of English and Malayalam, and packs local novelties like Onam greetings and Kerala jokes. It's offline-capable, customizable, and perfect for your Kanayannur setup.

Any issues? Raise an [issue](https://github.com/YOUR_USERNAME/tintu-ai-assistant/issues) (replace with your repo). Follow the setup below—tested on Python 3.11!

## About Tintu
Tintu started as a personal project to remix the classic JARVIS into something uniquely Kerala. Wake it with "Hey Tintu" and chat away in Manglish—no more stiff English-only bots. It's got that friendly neighborhood vibe, like calling out to a pal over chai.

**TINTU - Tony's Inspired Novel Natural Text Utility** (or just your go-to for "enthu vishesham?" moments).

Evolved from JoelShine's JARVIS: Started text-based, added speech, now fully AI with AIML + Kerala flair. Written in Python, runs smooth on Windows (recommended), macOS, or Linux. Minor audio tweaks for non-Windows.

Check the original JARVIS roots:
- First version (text-to-speech): https://github.com/JoelShine/JARVIS-The-Ultimate-Project
- Speech upgrade: https://github.com/JoelShine/Jarvis-v2.0

## Specialty of Tintu
<ul>
  <li>Fully autonomous with <b>AIML</b> and <b>Lisp</b> as the brain—handles chit-chat like a pro.</li>
  <li>Offline speech recognition with <b>Vosk</b> models (English base for Manglish; swap for full Malayalam).</li>
  <li>Natural <b>Malayalam/Manglish TTS</b> via gTTS—sounds like a Kochi local, not robotic!</li>
  <li>Solid program launching + custom Kerala commands (e.g., Onam ashamsakal, random jokes).</li>
  <li>Powerful chat mode with ALICE files, plus fallbacks for Manglish queries.</li>
  <li><b>Novelty Kerala Mode</b>: Weather for Kochi/Ernakulam, Onam vibes, and desi humor.</li>
</ul>

## Demo
Try these:
- Wake: "Hey Tintu"
- Joke: "Tintu joke paray" → Gets a random Kerala quip like "Njan rogiyalla, njan rogi da!"
- Weather: "Tintu Kochi weather" → "Lo 28 degrees, mazha varum undakoo."
- Greeting: "Tintu Onam ashamsakal" → Festive reply with pookalam tips.

(Upload a quick video to `/demo/tintu-demo.mp4` and link it here for GitHub stars!)

## Setup Procedures
Tested on Python 3.11—easy peasy for your laptop. Let's get Tintu chatting!

### Environment Setup
<ul>
  <li><h4>Python 3.7+ required (3.11 works great—no tweaks needed). Download 64-bit only for module compatibility. Add to PATH during install.</h4><br>
    Grab from https://www.python.org/downloads/<br>
    For 3.11: https://www.python.org/downloads/release/python-3110/ (Windows: python-3.11.0-amd64.exe).<br>
    Verify: Open CMD/Terminal, type `python --version`.</li>
 
  <li><h4>Ensure pip is ready: Type `pip` in CMD. If "not recognized," reinstall Python or fix via https://pip.pypa.io/en/stable/installation/.</h4></li>
 
  <li><h4>Pro tip for Kerala monsoons: Good mic helps with accents!</h4></li>
</ul>

### Installing Required Modules
<ul>
  <li><h4>Clone/fork this repo, open CMD in the folder, and run:</h4></li>
</ul>

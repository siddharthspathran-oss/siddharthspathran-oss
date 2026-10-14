<h1 align="center">Hi, I'm Siddharth </h1>
<p align="center">
  <b>Electronics &amp; Computer Engineering student at UPES Dehradun</b><br>
  I build things that sit between hardware and AI: assistants that actually <i>do</i> things, and the devices they live in.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C%23-.NET%2010-512BD4?style=flat&logo=dotnet&logoColor=white" alt="C# .NET">
  <img src="https://img.shields.io/badge/C%2B%2B-ESP32-00599C?style=flat&logo=cplusplus&logoColor=white" alt="C++ ESP32">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/LLMs-tool%20calling-8A2BE2?style=flat" alt="LLMs">
  <img src="https://img.shields.io/badge/PlatformIO-FF7F00?style=flat&logo=platformio&logoColor=white" alt="PlatformIO">
</p>

---

## 🛠️ What I'm building

### 🔮 Athena: a personal AI assistant for Windows <sub>(private repo)</sub>
A JARVIS-style assistant that runs on my own PC and actually controls it: about **31k lines of Python** and **155 tools**.

- **Voice:** wake word, Whisper speech recognition, Kokoro neural voice, and follow-up questions without the wake word
- **Agent:** quick routers handle common commands instantly; an LLM with tool calling (NVIDIA NIM / Groq, with a local Qwen fine-tune as fallback) plans everything else
- **Real actions:** opens apps and files, plays music, sends WhatsApp messages, controls my Android phone, joins my online classes in Teams with the mic and camera off
- **Study partner:** reads my university timetable, attendance and LMS, answers class questions as full pages with equations, circuit diagrams and graphs, and keeps "projects" of course files it searches (with OCR for scanned slides)
- **HUD:** a native desktop command centre plus a phone web app over Tailscale, with ChatGPT-style chats, automations, and a live activity feed
- **Safety:** permission tiers for risky actions, a prompt-injection guard on web/email content, and it never claims an action that didn't happen

### 💡 [Athena Desk Orb](https://github.com/siddharthspathran-oss/athena-desk-orb): hardware
An ESP32 desk companion: a glowing WS2812 ring inside a frosted dome, an INMP441 microphone, an LD2410C mmWave presence radar, BME280 and BH1750 room sensors, and an OLED. It talks to Athena over MQTT. I designed the 3D-printed enclosure in code (Python + manifold3d) and generate the STL files from parameters.

### 🖥️ Athena Desktop: Windows customisation in C#
A WPF / .NET 10 desktop layer: a Dynamic-Island-style notch that springs open into a control panel (media, stats, clipboard, apps, wallpapers, power) with spring-physics animation, and taskbar control through UI Automation.

### 🧪 [Lab Report Builder](https://github.com/siddharthspathran-oss/lab-report-builder)
Turns a lab manual and my readings into a finished Word report, with calculations, % error and formatting done for me, wired into Athena so I can just say "make my lab report for experiment 5".

---

## 📚 Currently learning
Embedded systems · LLM agents and retrieval

## 🤝 Let's connect
Open to internships and collaborations in **embedded systems, AI agents and automation**.

<!-- Add your links here, e.g.
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-HANDLE)
-->

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=siddharthspathran-oss&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=siddharthspathran-oss&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages">
</p>

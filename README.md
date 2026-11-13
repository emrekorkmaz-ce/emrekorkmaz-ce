<h1 align="center">Hi, I'm Emre Korkmaz 🛡️</h1>

<p align="center">
  <b>Cybersecurity Intern Candidate · SOC &amp; Log Analysis</b><br/>
  4th-year Computer Engineering student · Ankara, Türkiye
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/emrekorkmaz-ce/"><img src="https://img.shields.io/badge/LinkedIn-emrekorkmaz--ce-0A66C2?style=flat-square" alt="LinkedIn"/></a>
</p>

---

## 🔎 About Me

- 🎓 4th-year **Computer Engineering** student at Recep Tayyip Erdoğan University
- 🛡️ Focused on **threat detection, log correlation and incident response**, with the goal of growing as a **SOC analyst**
- 🧱 During my cybersecurity internship I built a **MITRE ATT&CK-based SIEM correlation engine from scratch**
- ⚖️ I don't stop at writing detection rules. I tune them so real traffic doesn't bury analysts in false positives, and I write down what the system *can't* see
- 🏁 Software team member of a **Teknofest 2026 Robotaxi finalist** team

---

## 🔭 Featured Project: [SIEM_with_Python](https://github.com/emrekorkmaz-ce/SIEM_with_Python)

A SIEM-style correlation engine written in Python **without any SIEM libraries**. It ingests Fortinet firewall logs over Syslog (UDP 514) in real time, normalizes them to JSON and raises alerts with MITRE ATT&CK-mapped correlation rules.

| Technique | Tactic | Detects |
|---|---|---|
| `T1595` Active Scanning | Reconnaissance | One source probing many ports |
| `T1110` Brute Force | Credential Access | Repeated attempts against the same target/port |
| `T1498` DoS | Impact | High request volume from a single source |
| `T1498` DDoS | Impact | Many sources converging on one target |

- ⚙️ **Producer-consumer pipeline** (multi-threaded + queue) that reduces UDP packet loss; load-tested at **~400 msg/s**
- 🎯 **Calibrated on real network traffic**: broadcast/multicast noise filter, DNS allowlist, threshold tuning
- 🔕 Per-rule cooldown cut alert volume from **33 to 4** (one alert per real event)
- ✅ Automated tests: **4 positive + 2 negative** attack scenarios
- 📝 Known limitations and next steps documented in the repo

---

## 💼 Experience

**Cybersecurity Intern** · *Jul – Aug 2026 · Ankara*
- Firewall log analysis and attack detection; designed and built the SIEM engine above

**Full-Stack Developer**, İŞKUR Gençlik Programı · *2025 – 2026*
- Built a corporate web application with React and .NET

---

## 📂 Other Projects

| Project | What it does | Stack |
|---|---|---|
| [Smart Campus Management System](https://github.com/emrekorkmaz-ce/Grup7_WebProje_Frontend) *(team project)* | Email-based 2FA and account verification, GPS attendance, genetic-algorithm course scheduling, real-time IoT tracking; deployed to GCP with GitHub Actions | Node.js · React · PostgreSQL · Docker · Socket.io |
| [Forest Guard](https://github.com/emrekorkmaz-ce/Forest-Guard) | ESP32-S3 forest-fire early-warning station with a voice assistant that runs on a **local LLM** (no cloud LLM APIs) | C (ESP-IDF) · Python · Flask · Ollama (Llama 3) · SQLite |
| [Jarvis Home Assistant](https://github.com/emrekorkmaz-ce/Home-Assistant) | Turkish voice home assistant on ESP32-S3 | C (ESP-IDF) · Python · Flask · Groq Whisper (STT) · LLaMA 3.3 70B · Edge TTS |

---

## 🏆 Achievements & Certifications

- 🏁 **Teknofest 2026, Robotaxi Autonomous Passenger Vehicle** (Ready Vehicle category): **Finalist**. Worked on image-processing-based perception
- 📜 **Cisco Networking Academy: Introduction to Cybersecurity** (Jul 2026)

---

## 🧰 Skills & Tools

| | |
|---|---|
| **Security** | ![SIEM](https://img.shields.io/badge/SIEM-Log%20Correlation-1F2937?style=flat-square) ![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-C8102E?style=flat-square) ![Fortinet](https://img.shields.io/badge/Fortinet-Log%20Analysis-EE3124?style=flat-square&logo=fortinet&logoColor=white) ![Syslog](https://img.shields.io/badge/Syslog-4B5563?style=flat-square) ![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=flat-square) ![Network Security](https://img.shields.io/badge/Network%20Security-0F766E?style=flat-square) |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square) |
| **Platforms & Tools** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| **Frameworks** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) |
| **Embedded / AI** | ![ESP32](https://img.shields.io/badge/ESP32--S3-E7352C?style=flat-square&logo=espressif&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) |

---

## 📚 Currently

- 🎓 This term: **Network Security**, **Secure Programming**, Data Mining, Data Science & Analytics, and my graduation thesis
- 🔬 Possible next steps for my SIEM engine: Sigma rule support, Sysmon / Windows Event Log sources, threat-intel enrichment and beaconing detection (`T1071`)

**Relevant coursework:** Cyber Security · Computer Networks · Operating Systems · IoT · Image & Video Processing · Fuzzy Logic & ANN

---

<p align="center"><i>🔐 Open to SOC / cybersecurity internship opportunities. Feel free to reach out on LinkedIn.</i></p>

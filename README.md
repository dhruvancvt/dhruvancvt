# Hi there, I'm Dhruva

Cybersecurity analyst working in threat intelligence, DFIR, and adversarial research. B.S. in Computer Science from Saint Mary's College of California (2025).

**Website:** [dhruvancvt.github.io](https://dhruvancvt.github.io)

## What I'm Working On

I'm a **Member of Technical Staff at a stealth-stage startup**, where I work across threat intelligence, digital forensics and incident response, and adversarial research.

Outside of work, I do independent anti-cheat forensics and malware analysis for FiveM gaming communities: live PC checks, loader reverse engineering, and cheat/bypass detection.

## Featured Projects

### malloop
**[malloop](https://github.com/dhruvancvt/malloop)** - A deterministic + agentic malware analysis pipeline. Samples are recursively unpacked (ZIP, DMG, 7z/RAR, with zip-bomb and path-traversal guards), triaged (hashes, entropy, IOCs, YARA, PE parsing), and run through static analysis with Ghidra headless, capa, and FLOSS. A Claude agent then drives follow-up analysis through a fixed, validated tool catalog (decompile, xrefs, string search, sandboxed detonation with Sysmon telemetry) and never gets a shell. Every run produces a report and a full action trace.

### DFIR Notes
**[dfir-notes](https://github.com/dhruvancvt/dfir-notes)** - My personal DFIR and malware analysis knowledge base. Includes sanitized real-world case write-ups (cheat loaders, DLL hijacking, COM-based bypasses, a keylogger with PCAP decryption), technique references on Windows forensic artifacts (Prefetch, AmCache, USB history, process hollowing, anti-forensics), HTB Sherlock write-ups, YARA detections, and a MITRE ATT&CK index across all cases.

### AI IP Detection
**[aiipdetection](https://github.com/dhruvancvt/aiipdetection)** - Machine learning system that identifies likely attackers from network IP datasets.

### Other Projects
- **[mediabiasdetection](https://github.com/dhruvancvt/mediabiasdetection)** - ML-based detection of bias in news articles
- **[arduinoProjects](https://github.com/dhruvancvt/arduinoProjects)** - Embedded systems and IoT projects

## Previous Experience

**Data Engineering Intern @ DynPro** - Built *Data Whisperer*, an AI-powered speech-to-SQL platform that turns natural-language questions into SQL queries and visualizations for non-technical users.

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white) ![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

**Security & Forensics**

![Ghidra](https://img.shields.io/badge/Ghidra-%23C8102E.svg?style=for-the-badge) ![YARA](https://img.shields.io/badge/YARA-%23333333.svg?style=for-the-badge) ![capa](https://img.shields.io/badge/capa-%23004B87.svg?style=for-the-badge) ![FLOSS](https://img.shields.io/badge/FLOSS-%23004B87.svg?style=for-the-badge) ![Sysmon](https://img.shields.io/badge/Sysmon-%230078D4.svg?style=for-the-badge) ![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-%23B31B1B.svg?style=for-the-badge) ![VirtualBox](https://img.shields.io/badge/VirtualBox-%23183A61.svg?style=for-the-badge&logo=virtualbox&logoColor=white) ![Hack The Box](https://img.shields.io/badge/Hack%20The%20Box-%23111927.svg?style=for-the-badge&logo=hackthebox&logoColor=9FEF00)

**AI & Data**

![Claude API](https://img.shields.io/badge/Claude%20API-%23D97757.svg?style=for-the-badge&logo=anthropic&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)

## Current Focus

- Agentic, LLM-assisted malware analysis with strict tool sandboxing
- Windows forensics and proving execution from host artifacts
- Cheat loader and bypass reverse engineering
- Threat intelligence and adversary tracking
- Detection engineering with YARA and ATT&CK mapping

# Drive-By-Download-Attack-Simulation
This project demonstrates a realistic Drive-by Download attack simulation in a controlled lab environment. The goal is to explore how attackers craft social engineering vectors and payload chains while providing cybersecurity defenders an educational example of what to look for.

# 🎯 Drive-by Download Simulation — Cybersecurity Educational Project

This project demonstrates a **Drive-by Download Attack Simulation** in a safe, offline lab environment for educational and awareness purposes. The setup mimics a fake Zoom/Teams software installer using social engineering and stealth payload delivery techniques.

> ⚠️ This simulation is **strictly for learning and ethical use only**. No unauthorized access or real-world attacks are permitted.

## 📁 Project Structure

project-root/ ├── web/ │ ├── index.html # Fake landing page for download │ ├── zoom.ico # Custom favicon/icon │ └── ZoomInstaller.exe # Obfuscated GUI + Payload Installer ├── payload/ │ ├── payload.exe # msfvenom/metasploit payload │ └── stage2.exe # Optional second-stage dropper ├── gui/ │ ├── installer.py # Python GUI script (Tkinter) │ └── ZoomSetup.spec # PyInstaller spec file ├── server/ │ └── logger.py # Flask app for logging victim activity ├── build/ │ └── ZoomInstaller.iss # Inno Setup script for packaging ├── report/ │ └── Project_Report.pdf # Detailed step-by-step documentation ├── README.md └── DISCLAIMER.md

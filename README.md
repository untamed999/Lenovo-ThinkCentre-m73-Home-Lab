# Lenovo-ThinkCentre-m73-Home-Lab
This Is A Personal Project To Teach Myself About Networking
# 🖥️ My Server Setup Journey

This repository documents how I’m setting up my personal server for learning, management, and experimentation.  
Hardware and software evolve as I add features step by step.

---

## ⚙️ Hardware
- Intel Core i5 (4th Gen)
- 16GB RAM
- 32GB SSD (system disk)
- 500GB HDD (storage disk)

---

## 🐧 Base OS
- **Ubuntu 24.04.3 LTS (Server Edition)**

---

## 📊 Server Management with Cockpit
Installed **Cockpit** for a web-based management interface.

### Installation
```bash
sudo apt update
sudo apt install cockpit cockpit-machines -y
sudo systemctl enable --now cockpit

# 🚘 Driver Drowsiness Detection using OpenCV & Machine Learning

A real-time **Driver Drowsiness Detection System** that monitors a driver’s eye activity through a webcam feed. If the driver’s eyes remain closed for a defined period (indicating drowsiness), the system triggers an audible alarm to alert the driver.

---

## 📌 Table of Contents
- [About](#about)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [How It Works](#how-it-works)
- [Installation](#installation)
- [Usage](#usage)
- [Project Demo](#project-demo)
- [Future Scope](#future-scope)
- [Screenshots](#screenshots)
- [Contributors](#contributors)
- [License](#license)

---

## ✅ About

This project aims to minimize road accidents caused by driver drowsiness. Using **OpenCV** and **Dlib facial landmarks**, it detects if the driver's eyes remain closed for too long and immediately triggers an alarm.

---

## 💻 Tech Stack

| Component      | Technology              |
|----------------|--------------------------|
| Language       | Python 3.x               |
| Face Detection | Dlib / OpenCV Haarcascade |
| Eye Tracking   | Facial Landmarks (Dlib)  |
| Alert Sound    | `playsound` or `winsound` |
| Interface      | Webcam Feed              |
| Libraries Used | `opencv-python`, `dlib`, `scipy`, `imutils`, `playsound` |

---

## ⭐ Features

- Real-time webcam monitoring
- Accurate eye detection using facial landmarks
- Eye aspect ratio (EAR) calculation
- Audible alarm if drowsiness is detected
- Lightweight and works on laptops with basic specs

---

## ⚙️ How It Works

1. Detects face and eyes using `dlib` facial landmarks
2. Calculates Eye Aspect Ratio (EAR)
3. If EAR remains below a threshold for several frames, the system:
   - Triggers an alarm sound
   - Displays an on-screen warning

---

## 🛠️ Installation

1. Clone the repository: "https://github.com/PrajwalMurali/driver_drowsiness" bash
   git clone 
   cd driver-drowsiness-detection




---

## 📁 Extra Tips for GitHub Repo:

- Add a `requirements.txt` file using:
  ```bash
  pip freeze > requirements.txt

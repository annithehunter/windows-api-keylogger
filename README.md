# Windows API Keylogger in Python (Educational Project)

## Overview

This project is a **Windows API-based keylogger** written in Python using **ctypes** and **wintypes**. Instead of relying on third-party libraries, it directly interacts with the Windows API to demonstrate how keyboard events can be monitored at a low level.

The application runs locally and records keyboard events while also identifying the active window where the input is being entered. This project was developed to better understand Windows internals, user input handling, and the techniques that security professionals need to recognize when analyzing malware or building defensive detections.

> **Disclaimer**
>
> This project was created **strictly for educational purposes, malware analysis, and authorized security research.**
> Running monitoring software on systems without explicit authorization may be illegal and unethical. The author is not responsible for any misuse of this project.

---

## Features

* Native Windows API implementation
* Written entirely in Python using **ctypes** and **wintypes**
* Monitors keyboard events locally
* Identifies the active application/window associated with keyboard input
* Lightweight implementation without external keyboard-hooking libraries
* Designed for educational research into Windows internals and malware analysis

---

## Technologies

* Python 3
* Windows API
* ctypes
* wintypes

---

## Learning Objectives

This project helped me understand:

* Windows API interaction from Python
* Calling native Win32 functions using `ctypes`
* Windows message handling
* Keyboard event processing
* Active window identification
* Low-level Windows programming
* Malware analysis fundamentals
* Endpoint detection concepts

---

## Project Structure

```text
.
├── keylogger.py
├── README.md
└── requirements.txt
```

---

## Installation

```bash
git clone https://github.com/annithehunter/windows-api-keylogger.git
cd windows-api-keylogger
```

No third-party packages are required if the implementation uses only the Python standard library and Windows APIs.

Run the program:

```bash
python keylogger.py
```

---

## Why Build This?

Understanding offensive techniques is an important part of becoming an effective cybersecurity professional. By learning how native Windows APIs can be used to monitor user input, defenders can better understand:

* How credential-stealing malware operates
* How endpoint detection and response (EDR) solutions identify suspicious behavior
* How security analysts investigate malicious software
* Why monitoring API usage is an important defensive strategy

---

## Future Improvements

* Improved logging format
* Timestamp support
* Better modularization
* Unit testing
* Detection-rule examples for defenders
* Documentation of the Windows API functions used

---

## Educational Use Only

This repository is intended solely for cybersecurity education, malware analysis, and authorized security testing. It should only be used in environments where you have explicit permission.

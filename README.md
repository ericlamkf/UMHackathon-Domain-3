# UMHackathon Domain 3
UMHackathon 2025 Domain 3 - Economic Empowerment through AI
![image](https://github.com/user-attachments/assets/5a4ab62e-db4b-41a9-a492-540a4c5209c7)
![image](https://github.com/user-attachments/assets/ab7c8eee-1dba-4f0c-9987-38801c083146)
![image](https://github.com/user-attachments/assets/f939ca49-fd16-4d1b-8468-3e213d9d0ace)
![image](https://github.com/user-attachments/assets/2e1148b1-1232-427c-9b94-398e79ff0c3c)

# 🎧 Grab Audio Transcription Assistant

This project is a prototype feature designed for **Grab’s driver-partners (DAX)**, allowing **automatic voice transcription** using the latest in speech-to-text technology. The goal is to provide *voice-centric interface, allowing driver-partners to receive assistance without the need to physically hold and type on their phones**, and of course to improve communication between **drivers and passengers**, even in noisy environments.

---

## 🚖 Problem Statement

In many ride-sharing situations:
- Drivers speaks in **different languages**
- There is **background noise** (traffic, people, weather)
- Misunderstandings from the voice assistant may lead to **frustrations and delays**, and even worse, **Accidents** 😱

This tool aims to solve that by providing a **lightweight, fast, and accurate transcription pipeline** that can work on-device or via cloud.

---

## ✅ Core Features

- 🎙️ Records short voice messages in-browser (simulating in-app recording)
- 🧠 Transcribes using OpenAI's Whisper model (proven on noisy, multilingual data)
- 🌐 Can handle multiple languages and accents， tailored for users from SEA
- 💡 Future-ready for translation, intent recognition, or chatbot flow

---

## 🧠 Why Whisper?

Whisper is trained on **680,000+ hours of multilingual and multitask supervised data** collected from the web. It performs well on:
- **Non-English speech**
- **Accented speakers**
- **Real-world noise**
- **Low-resource languages**

This makes it a perfect match for **Grab's diverse user base** across Southeast Asia.

---

## 🔁 Demo Flow

1. 🧑‍💻 User (driver/passenger) speaks a short message
2. 🎤 Audio is recorded using browser mic (simulate mobile app input)
3. 💾 Audio is saved as `.wav`
4. 🤖 Whisper transcribes it into plain text
5. 🪄 Text can then be translated, displayed, or used in chat

---

## 📍Figma Prototype Design
We have successfully developed a comprehensive Figma prototype that visually demonstrates the functionalities and workflow of our app, offering an intuitive and engaging representation of how users will interact with it.

Check out the Figma prototype here: [Figma Prototype](https://www.figma.com/design/f0fFGuKwL0JEWvd7gkqBL4/UM-Hackathon---DAX-Assistant?node-id=0-1&t=0QBHNRALLWQZTtDu-1)

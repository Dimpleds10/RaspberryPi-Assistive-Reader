# Raspberry Pi-Based Multilingual Assistive Reader 👁️🔊

🏆 **2nd Place – IEEE RCOEM SPS Hackathon (March 2024)**  

A Raspberry Pi-based OCR Text-to-Speech system designed to help visually impaired individuals convert printed text into audible speech.

---

## 📌 Introduction

There is a vast amount of printed material available today, and converting all of it into Braille is neither practical nor cost-effective. This creates a significant accessibility gap for visually impaired individuals.

To address this challenge, we developed a smart assistive device using Raspberry Pi that captures printed text and converts it into speech. The system processes images using Optical Character Recognition (OCR) and outputs clear audio through a speaker or headphones.

This solution is affordable, portable, and scalable.

---

## ⚙️ System Architecture

The system consists of three main units:

### 🔹 Input Unit
- IP Webcam for capturing printed text

### 🔹 Processing Unit
- Raspberry Pi 4
- Image preprocessing using OpenCV
- Text extraction using Tesseract OCR

### 🔹 Output Unit
- Google Text-to-Speech (gTTS)
- Audio playback via speaker/headphones

---

## 🔄 Working Process

1. Capture image using IP webcam  
2. Convert image to grayscale using OpenCV  
3. Extract text using Tesseract OCR  
4. Convert extracted text into speech using gTTS  
5. Play audio through connected speaker/headphones  

---

## 🌐 Language Support & Evolution

### Phase 1 – Initial Development (English)
- OCR Language: English (`eng`)
- TTS Language: English (`lang='en'`)
- Recognized text displayed on screen
- Spoken output in English

### Phase 2 – Hackathon Enhancement (Hindi)
During IEEE SPS Hackathon, judges suggested testing the system for Hindi language as well.

The system was successfully adapted to:
- Recognize Hindi text (`hin`)
- Convert Hindi text into speech (`lang='hi'`)
- Demonstrate live Hindi shayari conversion from printed text to speech

The hardware architecture remained unchanged. Only OCR and TTS language configurations were updated.

### Final Implementation
The system supports:
- English
- Hindi
- Combined multilingual configuration (`eng+hin`)

The Hindi version was successfully demonstrated in the competition video.

---

## 🛠 Hardware Components

- Raspberry Pi 4  
- IP Webcam  
- USB Speaker / Headphones  
- Micro SD Card  
- Power Supply  
- Laptop  

---

## 💻 Software & Libraries Used

- OpenCV  
- Tesseract OCR  
- gTTS (Google Text-to-Speech)  
- pyttsx3  
- mpg123  
- Motion (for IP camera monitoring)  

---

## 🎯 Key Advantages

- Enhances accessibility for visually impaired users  
- Cost-effective compared to commercial assistive devices  
- Portable and user-friendly design  
- Customizable language support  
- Open-source and extensible  

---

## 🏆 Result

The system successfully converts printed text into clear and understandable speech output, enabling visually impaired individuals to independently access written information.

This project secured **2nd Place at IEEE RCOEM SPS Hackathon (March 2024)**.

---

## 🧠 Conclusion

The Raspberry Pi-Based Assistive Reader demonstrates how affordable hardware and open-source tools can be combined to create impactful accessibility solutions.

By transforming printed text into audible speech, this project contributes toward building a more inclusive and accessible society.

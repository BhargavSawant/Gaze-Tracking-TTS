# 📖 AI-Powered Gaze-Tracking Reading Assistant  

An adaptive **reading assistant** that integrates **real-time gaze tracking, OCR, translation, and contextual meaning extraction** to enhance accessibility for learners, dyslexic readers, and visually impaired users.  

---

## 🚀 Features  
- 👀 **Real-Time Gaze Tracking** (OpenCV + Dlib) – maps eye movement to document text.  
- 🔊 **Adaptive Reading Support** – highlights text based on gaze; provides instant meanings/translations.  
- 📘 **Word Meaning Extraction** – integrates dictionary/translation APIs (Gemini API).  
- 🌐 **Multi-Language Translation** – translates text to user’s preferred language.  
- 📝 **Document Management** – upload, annotate, export, and manage reading sessions.  
- 👥 **Collaboration** – assign reviewers, share documents, and track reading progress.  
- ♿ **Accessibility-Driven Design** – supports dyslexic, visually impaired, and second-language learners.  

---

## 🛠️ Tech Stack  

| Layer              | Technology |
|--------------------|------------|
| **Frontend**       | HTML, CSS, JavaScript |
| **Backend**        | Python (Flask), WebSocket (Socket.IO) |
| **Computer Vision**| OpenCV, Dlib |
| **OCR**            | Tesseract OCR |
| **AI/Language**    | Gemini API |
| **Database**       | SQL (MySQL / PostgreSQL / SQLite) |
| **Tools**          | GitHub, VS Code, PlantUML |

---

## 🏗️ System Architecture  

![System Architecture](./diagrams/system_architecture.png)  
*(Generated from PlantUML – see `AI_GazeTracking_Assistant_SRS_Diagrams.puml`)*  

---

## 📂 Project Structure  

```bash
AI-GazeAssistant/
├── backend/                # Flask backend (Python)
│   ├── app.py              # Main server logic
│   ├── gaze_tracking.py    # OpenCV + Dlib modules
│   ├── ocr_processing.py   # Tesseract OCR module
│   ├── translation.py      # Gemini API integration
│   ├── database.py         # SQL data management
│   └── requirements.txt    # Python dependencies
│
├── frontend/               # Browser client (HTML/CSS/JS)
│   ├── index.html
│   ├── styles.css
│   └── app.js
│
├── diagrams/               # UML diagrams
│   └── AI_GazeTracking_Assistant_SRS_Diagrams.puml
│
├── docs/                   # Documentation
│   ├── SRS_Document.docx
│   ├── SRS_Document.pdf
│   └── references.md
│
└── README.md               # Project overview (this file)

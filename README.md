# 🤖 AI Business Assistant (n8n + OpenRouter)

An AI-powered Business Assistant built using **n8n**, **OpenRouter**, and **Google Workspace APIs**. The assistant intelligently detects user intent and automates multiple business tasks through a single conversational interface.

## 🎥 Demo Video

https://youtu.be/BSus61RA0T4

## 🚀 Features

- 📄 Resume ATS Analysis
- 📊 Stores Resume Data in Google Sheets
- 📧 AI Email Writer
- 📑 Saves Emails to Google Docs
- 📝 Meeting Notes Generator
- 📄 Stores Meeting Notes in Google Docs
- 💼 LinkedIn Post Generator
- 📄 Saves LinkedIn Posts to Google Docs
- 🧾 Invoice Generator
- 📊 Stores Invoice Details in Google Sheets
- 💬 General Business AI Assistant
- 🧠 Intent Routing using AI

---

## 🛠️ Tech Stack

- n8n
- OpenRouter AI
- Google Sheets API
- Google Docs API
- Gmail API
- JavaScript
- Prompt Engineering
- AI Agents

---

## 📌 Workflow

```
User Message
      │
      ▼
Intent Router (AI)
      │
      ▼
Switch Node
      │
      ├── Resume Analyzer
      ├── Email Writer
      ├── Meeting Tool
      ├── LinkedIn Tool
      ├── Invoice Generator
      └── General Assistant
```

---

## 📂 Modules

### 📄 Resume Analyzer
- Extracts candidate information
- Calculates ATS Score
- Identifies missing skills
- Provides hiring recommendation
- Stores candidate data in Google Sheets

---

### 📧 Email Writer
- Generates professional emails
- Saves generated email to Google Docs

---

### 📅 Meeting Tool
- Creates structured meeting notes
- Saves notes to Google Docs

---

### 💼 LinkedIn Tool
- Generates engaging LinkedIn posts
- Creates a new Google Doc
- Inserts the generated content automatically

---

### 🧾 Invoice Generator
- Generates invoice information
- Stores invoice data in Google Sheets

---

### 💬 General Assistant
- Answers general business-related questions
- Provides professional responses

---

## 📸 Screenshots

### Workflow
<img width="1169" height="593" alt="image" src="https://github.com/user-attachments/assets/c0384211-6f1e-4061-8059-85c9099240e5" />


### Resume Analyzer
<img width="1362" height="684" alt="image" src="https://github.com/user-attachments/assets/98b5e7cb-a6e0-4660-a578-7f5dea5b3c23" />


### LinkedIn Generator
<img width="1357" height="632" alt="image" src="https://github.com/user-attachments/assets/7a2ae5d3-8247-44e6-a4ce-51110c26657a" />


### Email Writer
<img width="1346" height="767" alt="image" src="https://github.com/user-attachments/assets/76f35dad-a6ee-4992-aec3-d08c2618968b" />


### Invoice Generator
<img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/443a88a3-ff2e-41d4-a819-a11ec5929d72" />


### Meeting Tool
<img width="1365" height="756" alt="image" src="https://github.com/user-attachments/assets/3dbd342c-810a-401a-8f56-8fa2ee5b4e37" />


---

## 🔮 Future Improvements

- PDF Resume Upload
- Google Calendar Integration
- WhatsApp Integration
- Telegram Bot
- Memory Support
- PDF Invoice Generation

---

## 📖 How to Run

1. Import the workflow JSON into n8n.
2. Connect your OpenRouter API key.
3. Connect Google Sheets, Docs, and Gmail credentials.
4. Publish the workflow.
5. Start chatting with the AI Business Assistant.


---

## ⭐ If you found this project useful, don't forget to star the repository!

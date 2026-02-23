<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d4227473-a761-4afc-9e1e-25b3346182b3" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/da4c543e-5edc-48bc-9efa-841c66280bab" />
# 📄 AI Resume Analyzer Automation (n8n + Groq)

An automated AI-powered workflow that analyzes resumes sent via email and returns structured feedback using Large Language Models.

When a user sends an email with a resume PDF attachment, the system automatically:

- Detects the incoming email  
- Extracts text from the attached resume  
- Sends the resume content to Groq LLM  
- Generates strengths, weaknesses, improvement suggestions, and ATS score  
- Sends the analysis back to the sender via email  

All steps run without any manual intervention.

---

## ⚙️ Tech Stack

- n8n (Workflow Automation)  
- Groq LLM API  
- Gmail API  
- PDF Text Extraction  

---

## 🔁 Workflow Overview

1. Gmail Trigger listens for emails with subject: `resume analysis`  
2. Email attachment (PDF) is extracted  
3. Resume text is sent to Groq Chat Model  
4. AI generates structured feedback  
5. Result is emailed back to the sender  

---

## ✅ Features

- Fully automated resume analysis  
- Works with PDF resumes  
- AI-powered feedback & ATS scoring  
- Reusable workflow (import/export JSON)  
- No-code + low-code architecture  

---

## 📂 Files

- `ai-resume-analyzer-workflow.json` → n8n workflow export  

---

## 🚀 How to Run Locally

1. Install n8n  
2. Import workflow JSON  
3. Configure Gmail credentials  
4. Configure Groq API key  
5. Activate workflow  

---

## 🎯 Use Cases

- HR resume screening  
- Career guidance platforms  
- Placement automation  
- Freelance automation services  

---

## 📌 Author

**Sabari M**

---

## ⭐ If you find this useful

Please star this repository to support the project 😊

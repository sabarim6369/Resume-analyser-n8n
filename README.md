<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d4227473-a761-4afc-9e1e-25b3346182b3" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/da4c543e-5edc-48bc-9efa-841c66280bab" />
📄 AI Resume Analyzer Automation (n8n + Groq)

This project is an automated AI-powered workflow that analyzes resumes sent via email and returns structured feedback using Large Language Models.

When a user sends an email with a resume PDF attachment, the system automatically:

Detects the incoming email

Extracts text from the attached resume

Sends the resume content to Groq LLM

Generates strengths, weaknesses, improvement suggestions, and ATS score

Sends the analysis back to the sender via email

All of this happens without manual intervention.

⚙️ Tech Stack

n8n (Workflow Automation)

Groq LLM API

Gmail API

PDF Text Extraction

🔁 Workflow Overview

Gmail Trigger listens for emails with subject: resume analysis

Email attachment (PDF) is extracted

Resume text is sent to Groq Chat Model

AI generates structured feedback

Result is emailed back to the sender

✅ Features

Fully automated resume analysis

Works with PDF resumes

AI-powered feedback & ATS scoring

Reusable workflow (import/export JSON)

No-code + low-code architecture

📂 Files

ai-resume-analyzer-workflow.json → n8n workflow export

🚀 Use Cases

HR resume screening

Career guidance tools

Placement cells

Freelance automation services

🧪 How to Run

Install n8n

Import workflow JSON

Add Gmail & Groq credentials

Activate workflow

📌 Author

Built by Sabari M

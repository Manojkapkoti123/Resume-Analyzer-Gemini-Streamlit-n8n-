# Resume-Analyzer-Gemini-Streamlit-n8n-
🎯 AI Resume Analyzer (Gemini + Streamlit + n8n)

An AI-powered ATS Resume Screening & Job Matching System built using Streamlit, Google Gemini API, and n8n automation. This application analyzes resumes against job descriptions,
calculates match scores, identifies skill gaps, and generates professional HR-ready candidate summaries through a modern ATS-style dashboard.

🚀 Features
✅ Upload resume in PDF format
✅ Paste Job Description
✅ AI-generated Match Score (0–100)
✅ Extracts:

Candidate Name
Email
Experience Level
Skills
Matching Skills
Missing Skills
✅ Professional HR Summary (No Raw JSON Displayed)
✅ Interactive Match Score Gauge
✅ Modern ATS-Style UI Dashboard
✅ Send candidate data to n8n workflow automatically
✅ Secure environment-based API key handling

Main Dashboard
imageimageimage
N8N Workflow Image
image
🛠️ Tech Stack
Frontend: Streamlit
AI Model: Google Gemini (gemini-2.5-flash)
PDF Processing: PyPDF2
Charts: Plotly
Automation: n8n Webhook
Backend: Python
API Handling: Requests
📂 Project Structure
📦 ai-resume-analyzer

┣ 📜 app.py

┣ 📜 requirements.txt

┣ 📜 README.md

┣ 📜 .env

┗ 📜 .streamlit/secrets.toml

🔐 Environment Setup
✅ 1. Create .env File (For Local Setup)
GEMINI_API_KEY=your_gemini_api_key_here

N8N_WEBHOOK_URL=your_n8n_webhook_url_here

✅ 2. For Streamlit Cloud Deployment
Create file:
.streamlit/secrets.toml

Add:
GEMINI_API_KEY="your_gemini_api_key_here"

N8N_WEBHOOK_URL="your_n8n_webhook_url_here"

📦 Install Dependencies
pip install -r requirements.txt

✅ requirements.txt
streamlit

google-generativeai

PyPDF2

plotly

requests

python-dotenv

▶️ Run the Application
streamlit run app.py

The app will open automatically in your browser.

📊 How It Works
Upload a Resume PDF
Paste the Job Description
Click Analyze Resume
Gemini AI:
Extracts candidate information
Matches skills with job requirements
Calculates match percentage
Generates professional summary
Results appear in a clean ATS-style dashboard
Candidate data is automatically sent to n8n workflow
🔄 n8n Webhook Payload Format
image
You can connect this to:
---- Google Sheets

---- Notion

---- Email automation

---- CRM

---- ATS systems

📸 UI Highlights
📊 Match Score Gauge

👤 Candidate Profile Card

✅ Matching Skills Panel

⚠️ Missing Skills Panel

📝 Professional Summary Section

📤 Workflow Automation Button

🔒 Security
✅ API keys are never hardcoded

✅ Environment variable protection

✅ Gemini failures handled safely

✅ JSON validation & fallback protection

✅ n8n webhook secured by secret URL

📈 Future Enhancements
✅ Bulk Resume Upload

✅ Candidate Ranking System

✅ Download Candidate Report as PDF

✅ Shortlist & Reject Buttons

✅ Resume Database

✅ Admin Dashboard

✅ Login System

✅ SaaS Deployment

✅ Email Automation

✅ Subscription Billing

👨‍💻 Author
Developed by: Manoj Singh

Role: Data Analyst

Project Type: AI-Powered ATS & Recruitment Automation System

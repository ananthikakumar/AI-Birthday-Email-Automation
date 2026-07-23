# 🎉 AI Birthday Email Automation using n8n

## 📌 Project Overview
This project automates birthday email wishes using n8n. It checks for birthdays, generates a personalized AI-powered birthday message, creates an HTML birthday card, compresses it into a ZIP file, and sends it as an email attachment through Gmail.

## 🚀 Features
- Automatic daily execution using Schedule Trigger
- Reads birthday data from Google Sheets or CSV
- Checks for today's birthdays
- Generates personalized birthday messages using AI
- Creates an HTML birthday card
- Compresses the card into a ZIP file
- Sends the ZIP file as a Gmail attachment
- Fully automated workflow

## 🛠️ Technologies Used
- n8n
- Gmail API
- AI Agent (OpenAI / Groq)
- HTML
- ZIP Compression
- Google Sheets / CSV

## 📂 Workflow

Schedule Trigger
↓
Read Birthday Data
↓
Check Today's Birthday
↓
Generate AI Birthday Message
↓
Create HTML Card
↓
Compress to ZIP
↓
Send Email via Gmail

## 📸 Screenshots
(Add workflow and email screenshots here.)

## ▶️ How to Run
1. Install Docker and n8n.
2. Import the `workflow.json` file into n8n.
3. Configure your Gmail credentials.
4. Configure your AI API key.
5. Enable the workflow.
6. The workflow will automatically send birthday emails every day.

## 📧 Output
The recipient receives:
- A personalized AI-generated birthday message
- A ZIP attachment containing the HTML birthday card

## 👩‍💻 Author
Ananthika Kumar

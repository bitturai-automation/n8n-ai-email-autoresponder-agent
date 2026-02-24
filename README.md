# 🚀 AI Email Auto-Responder Agent (n8n + OpenAI)

## 📌 Overview

This project is an AI-powered email automation system built using n8n, Gmail API, and OpenAI GPT-4.1.

The workflow automatically checks unread emails every 2 hours, extracts email content, and generates a professional reply draft using an AI Agent.

The system is designed to intelligently respond to business inquiries while filtering out promotions and collaboration requests.

---

## 🏗 Workflow Architecture

Schedule Trigger (Every 2 Hours)  
→ Fetch Unread Emails (Gmail)  
→ Retrieve Full Email Details  
→ AI Agent (Draft Professional Reply)  

---

## 🔄 How It Works

1. Workflow runs automatically every 2 hours.
2. Gmail node fetches unread emails (limit: 5).
3. Full email content and attachments are retrieved.
4. AI Agent processes the email body.
5. OpenAI GPT-4.1 drafts a professional response.
6. The output returns only the email body (clean draft format).

---

## 🤖 AI Prompt Logic

The AI is instructed to:

- Draft professional email replies
- Politely decline promotions & collaborations
- Express openness for meetings and project discussions
- Return only the email body text
- Maintain professional tone

---

## 🛠 Tech Stack

- n8n (Workflow Automation)
- Gmail API
- OpenAI GPT-4.1
- LangChain AI Agent Node
- Scheduled Automation Trigger

---

## 🎯 Key Features

- Automated unread email detection
- AI-powered reply drafting
- Professional tone generation
- Promotion filtering logic
- Clean output formatting
- Scheduled execution system

---

## 📊 Practical Use Cases

- Founder inbox automation
- AI-based email assistant
- Business inquiry handling
- Sales email filtering
- Automated response drafting
- Productivity automation system

---

## 🚀 Business Impact

- Reduces manual email drafting time
- Maintains professional communication
- Filters unwanted promotions
- Increases productivity
- Enables semi-autonomous inbox management

---

## 🔮 Future Enhancements

- Add automatic email sending (full automation)
- Add email categorization (sales / support / spam)
- Add CRM integration
- Add sentiment detection
- Add priority scoring
- Multi-account inbox support

---

## 📂 Repository Contents

- Email Filter and reply agent.json → n8n workflow export
- README.md → Documentation

---

## 👨‍💻 Author

Bittu Rai  
AI Automation Engineer  
GitHub: https://github.com/bitturai-automation  
LinkedIn: https://linkedin.com/in/bitturai  

---

⭐ Star this repository if you found it useful.


<img width="994" height="574" alt="image" src="https://github.com/user-attachments/assets/4f4e0574-56f9-4887-8530-0c804c45166b" />
<img width="1014" height="551" alt="image" src="https://github.com/user-attachments/assets/15880f77-2efe-4d88-a6a9-b4d43cf4429f" />
<img width="854" height="333" alt="image" src="https://github.com/user-attachments/assets/1f5f9015-698a-4c89-b1fe-411117c24e4e" />

# 🤖 AI Email Automation Assistant

🚀 A fully automated AI-powered email assistant built with **n8n** that reads, understands, and replies to unread emails — completely hands-free.

---

## 🌟 What This Project Does

This system automatically manages your inbox by:

- 📥 Fetching unread emails on a schedule  
- 🧠 Understanding email context using **Groq AI (LLM)**  
- ✉️ Generating and sending intelligent replies  
- 📊 Storing conversations in a database  
- 🧹 Keeping your inbox clean by marking emails as read  

👉 **Result:** Zero manual effort + Smart email management  

---

## ⚙️ Workflow Architecture

### ⏰ Schedule Trigger
Runs automatically at defined intervals:
- Every 5 min / 15 min / hourly / daily  

---

### 📩 Fetch Emails
- Retrieves unread emails from Gmail  

---

### 📑 Extract Data
Extracts key details:
- Subject  
- Body  
- Sender information  

---

### 🧠 AI Processing (Groq LLM)
- Understands email intent  
- Generates a smart reply  

---

### ✉️ Send Reply
- Automatically sends the generated response  

---

### 💾 Store Data
- Saves conversation for tracking and analysis  

---
### 📖 Mark as Read
- Marks the processed email as **read** after storing data and sending the reply  
- Prevents duplicate processing of the same email

---
## 🛠️ Tech Stack

- ⚡ n8n (Workflow Automation)  
- 🧠 Groq AI (LLM)  
- 📧 Gmail API  
- 🗄️ Database (Airtable / Notion / etc.)  

---

## 📌 Features

- ✅ Fully automated email handling  
- ✅ Smart AI-based replies  
- ✅ No manual intervention required  
- ✅ Scalable workflow  
- ✅ Clean and organized inbox  

---

## 🚀 How to Use

1. Import the workflow JSON into n8n  
2. Connect your Gmail account  
3. Add your Groq API key  
4. Set schedule trigger  
5. Activate the workflow  

---


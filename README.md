# AI Email Responder Bot using n8n

An automated AI email reply workflow built using **n8n**, **Gmail**, and **OpenRouter LLM**.  
The system monitors unread emails, processes them using defined conditions, generates AI-based replies, and sends responses automatically.

---

## 🚀 Features

- Gmail trigger for unread incoming emails  
- Sender-based email filtering  
- Reply detection to avoid duplicate responses  
- LLM-generated replies using OpenRouter   
- Automated email reply using Gmail API  
- Low-code workflow automation using n8n  

---

## 🧠 Workflow Overview

```text
Gmail Trigger
      ↓
Filter Emails (Sender + Status)
      ↓
Check Reply Condition
      ↓
Generate Response with LLM
      ↓
Send Gmail Reply
```

## Tech Stack
n8n
Gmail API
OpenRouter
Llama 3 Model
Prompt Engineering
Workflow Automation

## How It Works
The Gmail Trigger monitors unread emails from a defined sender
The workflow validates whether the email should be processed
The system checks if the email is already part of a reply thread
The email content is sent to an LLM for response generation
The generated reply is sent automatically via Gmail

## How to Use
Import workflow.json into n8n
Connect your Gmail OAuth2 credentials
Connect your OpenRouter API key
Update email filters if needed
Activate the workflow

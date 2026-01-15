# 🤖 MCP AI Lead Qualification System (n8n)

> **AI-powered conversational lead qualification & automation using n8n, Google Gemini, and MCP (Model Context Protocol)**

![n8n](https://img.shields.io/badge/n8n-Workflow_Automation-red)
![AI](https://img.shields.io/badge/AI-Google_Gemini-blue)
![MCP](https://img.shields.io/badge/MCP-Client--Server-green)
![Status](https://img.shields.io/badge/Status-Production_Ready-success)

---

## 🌟 Project Overview

This project demonstrates a **real-world AI automation system** where an intelligent chat agent **qualifies leads conversationally** and **automatically stores structured data** into Google Sheets.

Built using **n8n +  MCP**, this project follows a **clean client–server architecture** and is ideal for:

* Real estate businesses
* Sales & marketing teams

---

## 🧠 What This Project Does

✅ Talks to users via chat (AI Agent)
✅ Asks smart qualifying questions
✅ Extracts structured lead data
✅ Sends data using MCP Client
✅ Receives data via MCP Server
✅ Saves leads automatically to Google Sheets

---

## 🏗️ System Architecture

```
User Chat
   ↓
Chat Trigger (n8n)
   ↓
AI Agent (Google Gemini)
   ↓
MCP Client Tool
   ↓
MCP Server Trigger
   ↓
Google Sheets (Lead Database)
```

---

## 🧩 Workflows Included

### 1️⃣ MCP Client – Lead Qualification

**Purpose:** Conversational AI for lead qualification

**Key Nodes:**

* When Chat Message Received
* AI Agent
* Google Gemini Chat Model
* Simple Memory
* MCP Client Tool

**Sample AI Message:**

> *"Hi there! Welcome to Godrej Properties. Are you interested in finding out more about our apartments in Hinjawadi, Pune?"*

---

### 2️⃣ MCP Server – Lead Storage

**Purpose:** Secure data intake & storage

**Key Nodes:**

* MCP Server Trigger
* Google Sheets 

**Data Stored:**

* Name
* Contact details
* Preferred BHK
* Location

---

## 🛠️ Tech Stack

* **n8n** – Workflow Automation
* **Google Gemini** – Conversational AI
* **MCP (Model Context Protocol)** – Client–Server communication
* **Google Sheets API** – Lead storage
* **Simple Memory** – Context handling

---

## 📁 Repository Structure

```
📦 MCP-Lead-Qualification
 ┣ 📄 README.md
 ┣ 📄 mcp-client-lead-qualification.json
 ┣ 📄 mcp-server-lead-qualification.json
 ┗ 📁 images
    ┣ 📸 mcp-client-workflow.png
    ┗ 📸 mcp-server-workflow.png
```

---

## 🔁 Import & Run the Workflows

1. Open **n8n**
2. Click **Import from file**
3. Import both JSON files
4. Configure credentials:

Google Gemini API

Google Sheets OAuth

Activate both workflows

Start chatting 🚀

---

## 📊 Google Sheets Output

* Automatically appends new leads

* Acts as a lightweight CRM

* Ready for dashboards & analytics

---

---

## 🎯 Real-World Use Cases

* 🏢 Real Estate Lead Qualification
* 📞 Sales Chatbots
* 🤖 AI-powered CRM Intake
* 📋 Form Automation Replacement
---

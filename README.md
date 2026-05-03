# 💼 CRM Assistant Chatbot

> An intelligent WhatsApp-style chatbot that helps users find the perfect CRM for their business. Built with FastAPI (backend) and React (frontend). Features 8 major CRM companies with detailed comparisons, pricing, and smart recommendations.

## ✨ Features

- 🔐 **Phone Number Login** – Indian mobile number validation (10 digits, starts with 6-9)
- 💬 **Real-time Chat** – Auto-refresh every 2 seconds, smooth scrolling
- 🏢 **8 Preloaded CRM Companies** – Salesforce, HubSpot, Zoho, Freshsales, Pipedrive, Microsoft Dynamics, LeadSquared, Apptivo
- 📋 **List All CRMs** – View all companies with price, rating, and best use case
- 🔍 **Company Details** – Get complete info including features, website, free trial
- 📊 **Compare CRMs** – Side-by-side comparison of any two CRMs
- 🎯 **Smart Recommendations** – Based on business size (small/enterprise), budget, or free plans
- 🆓 **Free CRM Options** – See which CRMs offer free plans
- 💰 **Pricing Overview** – Budget, mid-range, premium, and enterprise price buckets
- 🎨 **Modern WhatsApp-like UI** – Clean, responsive, with quick-reply buttons
- 🗑️ **Clear Chat History** – Delete all messages for a user with confirmation
- 🧠 **In-memory Storage** – No database setup required – works out of the box

## 🛠️ Tech Stack

**Backend**  
- FastAPI
- Uvicorn
- Pydantic
- In-memory storage

**Frontend**  
- React (with Hooks)
- CSS-in-JS (inline styles)
- Fetch API

## 📦 Installation

### Prerequisites
- Node.js (v14+)
- Python (v3.8+)
- npm or yarn

### Clone the repository
```bash
git https://github.com/Sandeep-m-01/WhatsAppCRM/tree/main
cd WhatsAppCRM
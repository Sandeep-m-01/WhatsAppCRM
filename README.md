# CRM Assistant chatbot

An intelligent WhatsApp-style chatbot that helps users find the perfect CRM for their business. Built with FastAPI (backend) and React (frontend). Features 8 major CRM companies with detailed comparisons, pricing, and smart recommendations.

## Features

- Phone number login – Indian mobile number validation (10 digits, starts with 6-9)
- Real-time chat – Auto-refresh every 2 seconds, smooth scrolling
- 8 preloaded CRM companies – Salesforce, HubSpot, Zoho, Freshsales, Pipedrive, Microsoft Dynamics, LeadSquared, Apptivo
- List all CRMs – View price, rating, and best use case
- Company details – Features, pricing, website, free trial
- Compare CRMs – Side-by-side comparison of any two
- Smart recommendations – Based on business size, budget, or free plans
- Free CRM options – HubSpot, Zoho, Apptivo
- Pricing overview – Budget, mid-range, premium, enterprise buckets
- Modern WhatsApp-like UI – Clean, responsive, with quick-reply buttons
- Clear chat history – Delete all messages with confirmation
- In-memory storage – No database setup required

## Tech Stack

**Backend**  
- FastAPI  
- Uvicorn  
- Pydantic  
- In-memory storage

**Frontend**  
- React (with Hooks)  
- CSS-in-JS (inline styles)  
- Fetch API

## Installation

### Prerequisites
- Node.js (v14 or higher)
- Python (v3.8 or higher)
- npm or yarn

### Clone the repository
```bash
git clone https://github.com/Sandeep-m-01/WhatsAppCRM.git
cd WhatsAppCRM
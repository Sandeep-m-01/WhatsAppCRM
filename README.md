# WhatsApp CRM Simulation

This project is a simple web-based CRM system inspired by how businesses manage customer conversations on platforms like WhatsApp.

Instead of focusing only on UI, I built this to understand how real systems handle messages, APIs, and basic automation behind the scenes.

---

## What it does

* Simulates sending messages from a user (like WhatsApp)
* Stores and displays conversations based on phone number
* Allows replies from an “agent”
* Automatically responds to certain keywords (like "hello" or "price")
* Shows conversations in a simple CRM-style format

---

## Why I built this

I wanted to get a practical understanding of:

* How APIs handle communication between frontend and backend
* How customer interaction workflows are designed
* How automation (like auto-replies) works in real products
* How debugging and data flow work in a small system

This project is more about **logic and real-world flow** than just design.

---

## Tech stack

**Frontend**

* React

**Backend**

* FastAPI (Python)
* Uvicorn

**Tools**

* Postman (for testing APIs)

---

## Project structure

```id="9fpbwo"
WhatsappCRM/
├── backend/
│   ├── main.py
│   ├── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── package.json
│
└── README.md
```

---

## How to run it

### Backend

```id="p4u3s2"
cd backend
python3 -m venv venv
source venv/bin/activate   # Mac/Linux
pip install -r requirements.txt
uvicorn main:app --reload
```

Backend runs at:
http://127.0.0.1:8000

API docs:
http://127.0.0.1:8000/docs

---

### Frontend

```id="3rt0sn"
cd frontend
npm install
npm start
```

Frontend runs at:
http://localhost:3000

---

## API endpoints

**Send message**

```
POST /message/send
```

Example:

```id="7wscij"
{
  "phone": "9876543210",
  "message": "hello",
  "sender": "user"
}
```

**Get messages**

```
GET /messages/{phone}
```

**Get conversations**

```
GET /conversations
```

---

## Auto-reply logic

Right now, it’s simple:

* If user sends "hello" → send greeting
* If user sends "price" → send pricing message

This is a basic version of how chat automation works in real systems.

---

## What I learned

* Connecting frontend and backend using APIs
* Handling and debugging API responses
* Structuring a simple but meaningful workflow
* Thinking about real use cases instead of just features

---

## Future improvements

* Better UI (chat bubbles, sidebar layout)
* Database instead of in-memory storage
* Real WhatsApp API integration
* Deployment

---

## Author

Sandeep M
B.Tech CSE

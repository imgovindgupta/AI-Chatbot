# AI Customer Support Chatbot

## Project Overview
This project is an AI-powered customer support chatbot developed as part of the MSc Data Science and AI program.

The chatbot simulates a real-world support assistant that can handle common queries such as:
- Order tracking
- Refund requests
- General customer support questions

It uses a Large Language Model (LLM) via Groq API to generate intelligent responses.

---

## Objective
- Improve customer support efficiency using AI  
- Reduce response time for common queries  
- Demonstrate real-world usage of LLM-based chatbots  

---

## Features
- Interactive chatbot UI (Assistant UI)
- Real-time responses using Groq API
- Domain-specific responses using system prompts
- Handles basic customer support queries
- Scalable architecture

---

## Tech Stack
- Frontend: Next.js (Assistant UI)
- Backend: Node.js (API routes)
- LLM API: Groq API
- Environment: .env.local

---

## System Architecture
```
User → Chat UI → Backend (Node.js API) → Groq API → Response → UI
```

---

## Project Structure
```
chatbot/
│
├── app/
├── components/
├── hooks/
├── lib/
├── .env.local
├── package.json
└── README.md
```

---

## Installation & Setup

### 1. Clone Repository
```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install Dependencies
```
npm install
```

### 3. Add API Key
Create a `.env.local` file and add:
```
GROQ_API_KEY=your_api_key_here
```

### 4. Run Project
```
npm run dev
```

Open in browser:
```
http://localhost:3000
```

---

## Usage
Example queries:
- Where is my order?
- How can I get a refund?
- What is your return policy?

---

## Evaluation
The chatbot is evaluated based on:
- Response accuracy  
- Response time  
- Query handling capability  

---

## Limitations
- Depends on API availability  
- May generate incorrect responses  
- No database integration (prototype)

---

## Future Improvements
- Add database (orders, users)
- Improve response accuracy
- Add authentication system
- Deploy on cloud

---

## Author
Govind Gupta  
MSc Data Science and AI

---

## Important Note
Do NOT upload `.env.local` file to GitHub. Keep your API keys secure.

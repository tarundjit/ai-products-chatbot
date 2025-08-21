# 🤖 AI Products Chatbot (Beginner-Friendly)

This project is part of my journey to build an **AI Agency** from scratch.  
Here, I’m creating an **AI-powered Business Chatbot** that can:

- ✅ Answer customer FAQs from uploaded docs  
- ✅ Generate content (social media captions, emails, product descriptions)  
- ✅ Be deployed on a website for real businesses  

The project starts **no-code/low-code** (using [Flowise](https://flowiseai.com/)) and will evolve step by step with **version control** in GitHub.

---

## 📂 Project Structure

ai-products-chatbot/
│── flowise/ # exported chatbot flows (JSON)
│── exports/ # sample FAQs/docs for chatbot knowledge
│── docs/ # screenshots, demo notes
│── site/ # simple website to embed chatbot (later)
│── .env.example # environment template (API keys etc.)
│── .gitignore # ignore local + build files
│── README.md # this file (updated after each phase)


---

## 🛠️ Tech Stack
- **Flowise** → No-code AI workflow builder  
- **OpenAI GPT** → Chatbot brain  
- **Node.js + npm** → For running Flowise locally  
- **GitHub** → Version control + portfolio showcase  

---

## 🚀 Setup Guide (Phase 1)
1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/ai-products-chatbot.git
   cd ai-products-chatbot

2. Copy .env.example → .env and add your OPENAI_API_KEY.

3. Run Flowise:
    bash

    npm run flowise
    
4. Open http://localhost:3000 to access Flowise UI.


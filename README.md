# 🤖 AI Products Chatbot (Beginner-Friendly)

This project is part of my journey to build an **AI Agency** from scratch.  
Here, I’m creating an **AI-powered Business Chatbot** that can:

- ✅ Answer customer FAQs from uploaded docs  
- ✅ Generate content (social media captions, emails, product descriptions)  
- ✅ Be deployed on a website for real businesses  

The project starts **no-code/low-code** (using [Flowise](https://flowiseai.com/)) and will evolve step by step with **version control** in GitHub.

---

## 📂 Project Structure
```
ai-products-chatbot/
│── flowise/      # exported chatbot flows (JSON)
│   ├─ faq_chatbot.json
│   └─ content_helper.json
│── exports/      # sample FAQs/docs for chatbot knowledge
│   └─ business_faqs.md
│── docs/         # screenshots, demo notes
│── site/         # simple website to embed chatbot (later)
│── .env.example  # environment template (API keys etc.)
│── .gitignore    # ignore local + build files
│── README.md     # this file (updated after each phase)
```

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
   ```
2. Copy `.env.example` → `.env` and add your `OPENAI_API_KEY`.  
3. Run Flowise:
   ```bash
   npm run flowise
   ```
4. Open `http://localhost:3000` to access Flowise UI.

---

## 🧠 Current Flows (Phase 2)
### 1) FAQ Chatbot
- Location: `flowise/faq_chatbot.json`  
- Data source: `exports/business_faqs.md`  
- Purpose: Answers customer questions (returns, shipping, warranty, etc.).

### 2) Content Helper
- Location: `flowise/content_helper.json`  
- Purpose: Generates short marketing captions with hashtags.  
- Prompt variables (inside Chat Prompt Template): `brand`, `platform`, `product`, `tone`.

---

## 📅 Roadmap
This repo evolves in **phases**, each tracked with commits + branches:
- [x] **Phase 1** → Project setup + Flowise running ✅  
- [x] **Phase 2 (part 1)** → Build FAQ chatbot + content helper flows  
- [ ] **Phase 2 (part 2)** → Combine flows into a single business bot (router)  
- [ ] **Phase 3** → Deploy chatbot on a simple website  
- [ ] **Phase 4** → Add version control automation for flows & expand features  
- [ ] **Phase 5** → Package as a client-ready product  

---

## 🌟 Learning Goals
- Learn **AI product building** from scratch  
- Practice **no-code/low-code** AI dev with Flowise  
- Use **GitHub version control** for structured project growth  
- Build **portfolio-ready AI tools** for my future AI Agency  

---

✍️ *This README will be updated after every phase to reflect progress.*

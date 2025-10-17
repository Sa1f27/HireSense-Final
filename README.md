

<div align="center">
  <img src="frontend/public/logo-2.png" alt="HireSense Logo" width="400" />
  <p><b>AI-Powered Verification & Interview Engine for Authentic Hiring Decisions</b></p>
</div>

# HireSense: Hire with Certainty and Heart

**Beyond resumes, beyond interviews — discover the truth.**

HireSense is an AI-driven truth engine for hiring.  
In a world of curated resumes, it helps you uncover the authentic story of every candidate.  
By cross-validating digital footprints and conducting empathetic, AI-powered interviews, HireSense transforms uncertainty into confidence — helping you hire not just the most skilled, but the most trustworthy person for your team.

---

## 🚀 Live Demo

👉 [Watch Demo](https://drive.google.com/file/d/16zQ9rmsvcmj39we0hc2hYqt1gKJLmP1C/view?usp=sharing)  
📘 [View Presentation](https://gamma.app/docs/HireSense-49xvzsugsif1ojm)

---

## ✨ Key Features

### 🧬 Unified Candidate Story
**See the full truth at a glance.**
- **Cross-validates digital profiles** (CV, LinkedIn, GitHub)
- **Flags inconsistencies** in claims or achievements
- **Builds a single verified narrative** from fragmented data

### 🎙️ Empathetic AI Interviews
**Conversations that reveal character, not keywords.**
- **AI-powered candidate & reference calls** with natural conversation flow  
- **Deep transcript analysis** for tone, sentiment, and confidence  
- **Bias-free evaluation** through contextual understanding

### 🎯 The Certainty Score
**Move beyond gut feelings.**
- **AI-generated "Certainty Score"** combining verified data + sentiment analysis  
- **Actionable insights** highlighting red flags and hidden strengths  
- **Holistic credibility rating** for each candidate

### ⚙️ Seamless ATS Integration
**Keep your ATS as the source of truth — make it smarter.**
- **Effortless Ashby sync** to embed verification directly into workflow  
- **Automated documentation & summaries** reduce manual workload  
- **Focus on people, not paperwork**

---

## 🛠️ Tech Stack

- **Frontend:** Next.js • TypeScript • Tailwind CSS • Radix UI • Framer Motion  
- **Backend:** Supabase • PostgreSQL • pg_cron  
- **AI & NLP:** Groq API • OpenAI GPT-4 • ElevenLabs  
- **Infrastructure:** Docker • Vultr (Cloud Hosting)

---

## 🖼️ Screenshots

![6c7e4d77246249fc8080ae64d0dbd943](https://github.com/user-attachments/assets/4ea2dabf-4712-438a-bead-3d7b05968a07)

![IMG-20251017-WA0018](https://github.com/user-attachments/assets/2d23b911-e91f-4dae-a6cf-3065ae53c165)

![IMG-20251017-WA0017](https://github.com/user-attachments/assets/0307555b-8fe3-452e-9a22-76f4d1a708c8)

![IMG-20251017-WA0016](https://github.com/user-attachments/assets/f7c3cdc4-5cf9-4066-804f-cbdf7bb96123)

---

## 🔧 Local Setup

1. **Clone this repo**
   ```bash
   git clone https://github.com/<username>/HireSense.git
   cd HireSense/frontend
   ````

2. **Install dependencies**

   ```bash
   npm install  # frontend
   npm install -g pnpm
   pnpm supabase start # first run Docker
   cd backend && pip install -r requirements.txt && python main.py
   ```

3. **Configure environment variables**

   * Create `.env` file from `.env.example`
   * Add your API keys for OpenAI, Groq, and Supabase

4. **Run locally**

   ```bash
   pnpm dev
   ```

> Requires **Node.js 18+**.
> Docker is optional for running Supabase or PostgreSQL locally.

---

## 👥 Team

| Name                        | Role                 |
| --------------------------- | -------------------- |
| **Mohammed Huzaifah**       | AI and Integration Engineer     | 
| Mohammed Murtaza Uddin Maaz | Full-Stack Developer |
| Syed Numaan                 | Frontend Engineer    |
| Syed Abdul Muqeet Mujeeb    | Backend Developer    | 

---

<div align="center">
  <b>HireSense — Replacing uncertainty with undeniable proof.</b>
</div>


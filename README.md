# AIDrivenRecruitmentWorkflow

This Repo Contains The AI Driven Recruitment Workflow


# 🤖 AI-Driven Recruitment Workflow

> **An intelligent end-to-end recruitment automation system powered by AI, React, and Supabase.**  
> Simplify job posting, candidate applications, evaluation, and communication — all in one automated flow.

---

## 🧩 Overview

The **AI-Driven Recruitment Workflow** automates the entire hiring pipeline — from job posting to candidate evaluation and feedback.  
It’s designed for **companies** and **candidates** to interact effortlessly, while **AI agents** handle all the heavy lifting behind the scenes.

Built using:
- ⚛️ **React** for frontend
- 🗄️ **Supabase** for data storage
- 🧠 **LLaMA (Hugging Face)** for AI-based analysis
- 🔗 **Webhooks** and **Email Automation** for real-time communication

---

## 🚀 Features

✅ **AI-Powered Job Screening** — Generates smart interview questions & candidate evaluations  
✅ **Automatic Email Updates** — Sends tailored emails to both candidates and companies  
✅ **End-to-End Workflow** — From posting jobs → applying → evaluation → decision  
✅ **Fully Synced Database** — All data stored and managed in **Supabase**  
✅ **Smart Rating System** — AI rates candidates across 5 performance categories  
✅ **One-Click Shortlist/Reject** — Company can decide directly via email link  

---

## 🏢 Company Flow

1. **Post a Job** via the React web page  
   - Company Name  
   - Description  
   - Notification Email  
   - Job Title  
   - Job Requirements  

2. **Workflow Actions**  
   - Data is stored in `company` table (Supabase).  
   - AI Agent generates **10 custom interview questions** based on requirements.  
   - Job instantly appears in the “Apply for Job” dropdown for candidates.  

3. **Receive Applications Automatically**  
   - Company receives an email with candidate details, summary, and ratings.  
   - Option to **Shortlist** or **Reject** with a custom message.

---

## 👨‍💼 Candidate Flow

1. **Apply for a Job** by filling out:
   - Full Name  
   - Email  
   - Phone Number  
   - Job Title (auto-linked from company postings)  
   - CV (PDF Upload)  
   - Short Motivation Paragraph  

2. **AI-Powered Evaluation**
   - CV summary generated using **LLaMA via Hugging Face**  
   - AI compares CV with job requirements and produces:
     - Profile Summary  
     - Ratings in 5 key categories  

3. **Automatic Communication**
   - Candidate receives application confirmation.  
   - If **shortlisted**, they receive:
     - A “Shortlisted” email with a note.  
     - A second email with **10 AI-generated questions** to answer.  
   - Once they reply, the AI re-evaluates and sends final insights to the company.

---

## 📊 Workflow Summary

| Step | Action | AI Involvement |
|------|---------|----------------|
| 1 | Company posts job | Generates 10 questions |
| 2 | Candidate applies | Summarizes CV & rates profile |
| 3 | Company reviews | Receives ratings & summary |
| 4 | Company shortlists | Candidate gets questions |
| 5 | Candidate replies | AI re-evaluates answers |
| 6 | Final evaluation | Email sent to company with full report |

---

## 🗄️ Database Structure (Supabase)

| Table | Description |
|--------|--------------|
| `company` | Stores company info and job details |
| `job_questions` | Contains AI-generated questions for each job |
| `candidate` | Stores candidate data, summaries, and scores |

---

## ⚙️ Tech Stack

| Layer | Technology |
|--------|-------------|
| Frontend | React.js + TailwindCSS |
| Backend | Supabase |
| AI Engine | LLaMA (Hugging Face API) |
| Automation | Webhooks + AI Agents |
| Email | Gmail Integration |
| Hosting | Compatible with Vercel / Netlify |

---

## 🧠 AI Agents Responsibilities

- Generate **custom interview questions** based on job descriptions  
- Summarize **candidate CVs**  
- Evaluate responses and **score candidates** across 5 dimensions  
- Draft **email summaries** for both companies and candidates  

---

## 🧩 Customization

This workflow is modular — you can integrate:
- Advanced LLMs (e.g., GPT, Claude, Gemini)  
- Internal HR or ATS systems  
- Real-time dashboards for recruitment insights  
- Automated scheduling tools for interviews  

---

## 🏁 Why This Workflow

Hiring doesn’t need to be manual anymore.  
This system delivers:
- ⚡ Speed  
- 🎯 Accuracy  
- 🤝 Transparency  
- 📈 Efficiency  

For recruiters, it’s an intelligent assistant.  
For candidates, it’s a smoother experience.

---

## 🧑‍💻 Developer

**Abdul Rehman (Solo)**  
💼 AI Workflow & Automation Developer  
📧 abdulrehman657.pk@gmail.com

---

## 🪄 Demo Summary

> - Post a Job → AI Generates Questions  
> - Candidate Applies → AI Evaluates  
> - Company Reviews → Shortlists/Rejects  
> - AI Sends Questions → Evaluates Answers  
> - Company Receives Final Candidate Report  

**Everything** happens automatically — powered by your workflow logic and AI intelligence.  

---

### ⭐ Star this repo if you find it useful!

---


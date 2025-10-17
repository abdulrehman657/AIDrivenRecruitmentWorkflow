# AIDrivenRecruitmentWorkflow

This Repo Contains The AI Driven Recruitment Workflow


🤖 AI-Driven Recruitment Workflow
Automate Hiring — Smarter, Faster, and Effortlessly with AI

This project is a complete AI-powered recruitment automation system designed to simplify and speed up the hiring process for both companies and candidates.
It leverages React, Supabase, webhooks, and AI agents to handle everything — from job posting to candidate evaluation — automatically.

🚀 Overview

The AI Recruitment Workflow enables:
Companies to post job listings instantly.
Candidates to apply for jobs seamlessly.
AI agents to analyze, score, and summarize candidate profiles and generate interview questions.
Automatic email updates at every stage — ensuring a smooth and transparent experience.
This system saves hours of manual screening, delivers AI-generated insights, and keeps the entire process centralized in Supabase for full visibility.

🧠 How It Works
🏢 For Companies

Fill out a simple form with:

Company Name & Description
Notification Email
Job Title & Requirements
On submission:
Data is stored in Supabase (company table).
An AI agent generates 10 intelligent job-specific questions.
The job is instantly available for candidates to apply.

👨‍💼 For Candidates

Select a job from the dropdown (auto-linked to company postings).

Submit:

Full Name
Email & Phone Number
CV (PDF)
A short motivation paragraph

Workflow:

CV is summarized using LLaMA via Hugging Face API.
AI compares CV summary + job requirements → generates profile summary + 5 category ratings.
Application details & evaluation are emailed to both candidate and company.

✉️ AI-Enhanced Communication Flow

Candidate Receives:

Confirmation email

Notification upon shortlisting or rejection

A follow-up email containing the 10 AI-generated interview questions

Company Receives:

Application summary with candidate ratings & AI-generated insights

Follow-up after candidate responds to interview questions

⚙️ Decision & Follow-Up

Company can shortlist or reject candidates directly from the email link.

The system automatically sends appropriate personalized emails to the candidate.

Final reports and ratings are emailed back to the company for review.

🗄️ Tech Stack
Component	Technology
Frontend	React.js + TailwindCSS
Backend & Database	Supabase
AI Engine	LLaMA (HuggingFace API)
Automation & Webhooks	Custom Webhooks + AI Agents
Email Automation	Gmail Integration
Hosting	Compatible with Vercel / Netlify
📊 Supabase Structure
Table	Purpose
company	Stores job posting details
job_questions	Stores AI-generated questions per job
candidate	Stores candidate profiles, summaries & ratings
💡 Key Features

✅ AI-Powered Screening — Automatically evaluates candidates on 5 skill categories
✅ Automated Email Flow — Keeps both company & candidate informed
✅ Dynamic Question Generation — Unique job-based interview questions
✅ Seamless Integration — Everything stored and synced via Supabase
✅ One-Click Decisions — Approve or reject directly from email links

📩 Example Workflow Summary

Company posts a new job → AI creates questions

Candidate applies → AI summarizes CV

Company receives profile + scores

Candidate gets shortlisted → AI sends questions

Candidate answers → AI re-evaluates → Company notified

Every step is automated, tracked, and intelligently managed.

🧩 Customization

This is a demo version — you can easily:

Integrate advanced LLMs (e.g., GPT, Claude, Gemini)

Add real-time dashboards for HR teams

Plug in ATS or CRM systems

Automate scheduling interviews and follow-ups

🏁 Conclusion

This workflow is a next-generation hiring solution — built to reduce manual effort, improve candidate experience, and empower companies with AI insights at every step.

You can integrate it with your company’s internal HR tools or expand it into a full AI recruitment platform.

🔗 Author

Abdul Rehman
💼 Developer | AI Workflow Designer
📧 Abdulrehman657.pk@gmail.com

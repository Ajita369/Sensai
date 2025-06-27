# Sensai

[![Next.js](https://img.shields.io/badge/Framework-Next.js-black?logo=next.js)](https://nextjs.org/) [![Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind%20CSS-blue?logo=tailwind-css)](https://tailwindcss.com/) [![Prisma](https://img.shields.io/badge/ORM-Prisma-blue?logo=prisma)](https://www.prisma.io/) [![NeonDB](https://img.shields.io/badge/Database-NeonDB-00FFFF?logo=postgresql)](https://neon.tech/) [![Inngest](https://img.shields.io/badge/Workflow-Inngest-purple?logo=inngest)](https://www.inngest.com/) [![Shadcn UI](https://img.shields.io/badge/UI-Shadcn--UI-white?logo=shadcn)](https://ui.shadcn.com/) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **Sensai** — the full-stack AI Career Coach that helps you build your resume, cover letter, skills assessment and industry insights all in one place.

---

## About

Sensai is a modern, full-stack web app that leverages generative AI and serverless workflows to help job seekers:

- ✍️ **Generate** high-quality resumes & cover letters tailored to roles.  
- 📊 **Assess** technical & behavioral skills with AI-powered quizzes & tips.  
- 📈 **Explore** industry trends, salary ranges, and in-demand skills.  
- 💾 **Save** and download your profiles in Markdown or PDF.  

Visit the live demo: [sensai-chi.vercel.app](https://sensai-chi.vercel.app)  

---

## Features

- **User Authentication & Profiles**  
  - Sign up / Sign in with [Clerk.dev](https://clerk.dev)  
  - Store profile details: bio, experience, skills, industry  

- **Resume Builder**  
  - AI-powered resume generation via Google Generative AI  
  - ATS-friendly Markdown preview & PDF export  

- **Cover Letter Generator**  
  - Generate personalized cover letters from job description & role  

- **Skill Assessments**  
  - Quizzes across Technical & Behavioral categories  
  - Interactive question/answer review & AI-driven improvement tips  

- **Industry Insights**  
  - Salary ranges, growth rates, top skills per industry  
  - Market outlook, key trends 

- **Background Workflows**  
  - Asynchronous AI tasks & via Inngest  

---

## Tech Stack

- **Frontend**  
  - Next.js 15 (App Router)  
  - React 19 + Shadcn UI + Radix Primitives  
  - Tailwind CSS + `tailwindcss-animate`  
  - `react-hook-form`, `react-markdown`, `recharts`

- **Backend & API**  
  - Next.js Server Actions & API Routes  
  - Prisma ORM + PostgreSQL (Neon DB)  
  - Clerk.dev for authentication  
  - Inngest for background jobs  
  - Google Generative AI (`@google/generative-ai`)

---

## Getting Started

### Prerequisites

- Node.js ≥ 18  
- npm / yarn / pnpm  
- A PostgreSQL database (Neon recommended)  
- Clerk.dev account  
- Google Cloud API Key for Generative AI  

### Installation

```bash
# 1. Clone the repo
git clone https://github.com/Ajita369/Sensai.git
cd Sensai

# 2. Install dependencies
npm install
# or
yarn
# or
pnpm install

# Running locally
npm run dev
```
Open http://localhost:3000 in your browser.


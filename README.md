# 🚀 Skills Mirage

### India's Open Workforce Intelligence System

Skills Mirage is an AI-powered workforce intelligence platform that transforms **live job market signals into personalized reskilling paths for workers**.

Built during a hackathon to help India's workforce adapt to **AI-driven job disruption and evolving skill demands**.

---

# 🌍 Problem

India generates millions of job listings every month, yet:

* 45% of employers cannot find workers with the right skills
* Workers receive generic advice like “learn Python” without market context
* Automation and AI are rapidly replacing certain job roles
* Workers lack visibility into **future job demand in their cities**

There is currently **no open system that connects job market signals with career guidance**.

---

# 💡 Solution

Skills Mirage bridges this gap by analyzing job market data and generating actionable insights for workers.

The system provides:

• Hiring trends across cities and sectors
• Skills demand intelligence
• AI automation vulnerability index
• Personal AI risk score for workers
• Week-by-week reskilling roadmap
• AI career assistant chatbot

---

# 🧠 System Architecture

Skills Mirage operates using a **two-layer intelligence architecture**.

### Layer 1 — Job Market Intelligence

Analyzes job listings and labor market data to detect:

* Hiring trends
* Skills demand
* Automation vulnerability signals

Outputs a **real-time job market dashboard**.

### Layer 2 — Worker Intelligence Engine

Workers provide:

* Current job title
* City
* Years of experience
* Short work description

The system generates:

* AI risk score
* Career transition suggestions
* Reskilling roadmap
* AI chatbot guidance

---

# 📊 Core Features

## Hiring Trends Dashboard

Visualizes hiring patterns across cities, industries, and time periods.

## Skills Intelligence

Identifies **rising and declining skills** in the job market.

## AI Vulnerability Index

Scores job roles from **0–100 based on automation risk signals**.

## Worker Risk Analysis

Generates a **personalized AI risk score** for each worker.

## Reskilling Path Generator

Creates structured learning paths using **NPTEL, SWAYAM, and PMKVY courses**.

## AI Career Chatbot

Provides career guidance using worker profiles and market intelligence.

Supports **English and Hindi queries**.

---

# 🧩 Tech Stack

### Frontend

React / Next.js
Tailwind CSS
Shadcn UI
Recharts

### Backend

Python
FastAPI

### AI & Data

OpenAI / Gemini
NLP skill extraction
Market signal analysis

### Database

Supabase

---

# 📂 Project Structure

skills-mirage
│
├── frontend
│   ├── dashboard
│   ├── worker-engine
│   └── chatbot
│
├── backend
│   ├── data-pipeline
│   ├── risk-model
│   └── api
│
├── datasets
│
├── docs
│
└── README.md

---

# 📈 Data Sources

The system integrates open datasets including:

* Naukri job postings
* LinkedIn job listings
* NPTEL course catalog
* SWAYAM course platform
* PMKVY training programs
* PLFS labour market data

---

# 🔄 How It Works

1. Job listings are collected and analyzed
2. Hiring trends and skills signals are extracted
3. Automation vulnerability scores are calculated
4. Worker profile is analyzed
5. AI risk score is generated
6. A personalized reskilling roadmap is created

---

# 🎬 Demo Flow

1. Open Job Market Dashboard
2. Explore hiring trends and risk signals
3. Enter worker profile information
4. Generate AI Risk Score
5. View personalized reskilling roadmap
6. Ask questions using the AI chatbot

---

# 🖥 Installation

Clone the repository:

git clone https://github.com/your-username/skills-mirage.git

Navigate to the project folder:

cd skills-mirage

Install dependencies:

npm install

Run development server:

npm run dev

---

# 🔮 Future Improvements

• Real-time job market data pipeline
• Employer skill gap analytics
• Worker displacement early warning system
• Mobile career assistant app
• AI-driven career trajectory prediction

---

# 👨‍💻 Team

Built during a hackathon to develop an **open workforce intelligence system for India's workforce**.

---

# ⭐ Vision

Skills Mirage aims to become **India's first open workforce intelligence platform**, helping millions of workers navigate the rapidly evolving job market.

#🏗 System Architecture

                ┌───────────────────────────────┐
                │       Job Market Data         │
                │  Naukri • LinkedIn • PLFS     │
                └──────────────┬────────────────┘
                               │
                               ▼
                    ┌───────────────────┐
                    │ Data Processing   │
                    │ Scraping + NLP    │
                    └─────────┬─────────┘
                              │
                              ▼
                ┌──────────────────────────┐
                │ Layer 1: Market Engine   │
                │                          │
                │ Hiring Trends            │
                │ Skills Intelligence      │
                │ AI Vulnerability Index   │
                └───────────┬──────────────┘
                            │
                            ▼
                ┌──────────────────────────┐
                │ Layer 2: Worker Engine   │
                │                          │
                │ Worker Profile Input     │
                │ Risk Score Generator     │
                │ Reskilling Path Engine   │
                │ AI Career Chatbot        │
                └───────────┬──────────────┘
                            │
                            ▼
                ┌──────────────────────────┐
                │      User Interface      │
                │ Dashboard + Career Tool  │
                └──────────────────────────┘

# 🖥 UI Demo

## Job Market Dashboard
Shows hiring trends, skills demand, and AI vulnerability across cities.
![Dashboard](docs/images/Dashboard.png)

## Worker Risk Analysis
Users enter their job profile and receive a personalized AI risk score.
![Risk Score](docs/images/Risk Score.png)

## Reskilling Roadmap
Displays a structured week-by-week learning path.
![Reskilling Path](docs/images/reskilling.png)

## AI Career Chatbot
Interactive assistant that answers career questions using market data.
![Chatbot](docs/images/ChatBot.png)

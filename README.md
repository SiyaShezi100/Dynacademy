# Dynacademy

Dynacademy is an AI-powered education and career guidance platform designed to help South African learners make smarter academic and career decisions through Artificial Intelligence.

## Live Website

https://dynacademy.base44.app

---

# Overview

Dynacademy combines AI technologies, educational support systems, career guidance, and analytics into one modern platform.

The platform helps learners with:
- Career guidance
- APS score calculations
- University & TVET matching
- AI study assistance
- Bursary recommendations
- Student wellness support
- CV & motivation letter generation
- Future career insights

---

# Features

## AI Career Guidance
- Personalized career recommendations
- Degree and diploma suggestions
- Career pathway analysis
- Future job recommendations

## APS Calculator
- Automatic APS calculations
- University eligibility prediction
- Admission readiness analysis

## University & TVET Matching
- University recommendations
- TVET college matching
- Institution filtering by APS and location

## AI Study Assistant
- AI-generated summaries
- Quiz generation
- Study timetables
- Academic question answering

## AI Chatbot
- Educational support
- Career advice
- University information
- Study guidance

## Bursary Finder
- Bursary recommendations
- Financial aid support
- Career-based bursary matching

## Student Wellness
- Mood tracking
- Productivity support
- Stress management assistance
- Motivational suggestions

## Accessibility Features
- Large text mode
- Keyboard navigation
- Voice navigation
- High contrast mode
- Mobile responsiveness

## Multilingual Support
Supports multiple South African languages.

---

# Technology Stack

| Technology | Purpose |
|---|---|
| React | Frontend Framework |
| Vite | Build Tool |
| Tailwind CSS | Styling |
| Framer Motion | Animations |
| Firebase / Supabase | Authentication & Database |
| OpenAI API | AI Processing |
| Recharts / Chart.js | Analytics & Charts |
| JavaScript / TypeScript | Application Logic |

---

# System Architecture

## Frontend
- Responsive dashboards
- Interactive UI
- Modern glassmorphism design

## Backend
- Authentication
- API integrations
- AI request handling

## AI Layer
- Career recommendations
- Summarization
- Quiz generation
- AI chatbot responses

## Database
- User profiles
- Recommendations
- Analytics
- Notifications

---

# Installation

## Clone Repository

Navigate to Project
cd dynacademy
Install Dependencies
npm install
Run Development Server
npm run dev
Project Objectives

Dynacademy aims to:

Improve educational accessibility
Support career decision-making
Enhance learner productivity
Modernize educational support using AI
Provide intelligent educational assistance
User Roles
Student

Access:

AI tools
Career guidance
APS calculator
Study assistant
Bursary finder
Administrator

Access:

System management
Analytics
User monitoring
Configuration tools
Security Features
Secure authentication
Protected routes
Encrypted sessions
Input validation
Secure API communication
Future Enhancements
Mobile applications
Advanced AI personalization
LMS integration
Real-time university applications
Offline support
AI interview preparation
Team Members

Dynamic Tech Squad

Sinakhokonke Buthelezi
Ncamisile Ntuli
Siyabonga Shezi
Lerato Zitha
Atsho Nota
Educational Purpose

This platform was developed as an academic and innovation project focused on improving educational accessibility and career readiness through Artificial Intelligence.

License

This project is for educational purposes only.


Dynacademy is described in your documentation as an AI-powered education and career guidance platform that combines career guidance, APS calculations, university matching, AI study assistance, bursary recommendations, and wellness support into one centralized system. :contentReference[oaicite:0]{index=0}

---

# Simple Landing Page Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dynacademy</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, sans-serif;
    }

    body{
      background: linear-gradient(135deg,#0f172a,#1e3a8a);
      color:white;
      min-height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      text-align:center;
      padding:20px;
    }

    .container{
      max-width:800px;
    }

    h1{
      font-size:60px;
      margin-bottom:20px;
    }

    p{
      font-size:20px;
      line-height:1.7;
      margin-bottom:30px;
      color:#dbeafe;
    }

    .btn{
      display:inline-block;
      padding:15px 30px;
      background:#2563eb;
      color:white;
      text-decoration:none;
      border-radius:10px;
      font-size:18px;
      transition:0.3s;
    }

    .btn:hover{
      background:#1d4ed8;
      transform:scale(1.05);
    }

    .features{
      margin-top:50px;
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
      gap:20px;
    }

    .card{
      background:rgba(255,255,255,0.1);
      padding:20px;
      border-radius:15px;
      backdrop-filter: blur(10px);
    }

    .card h3{
      margin-bottom:10px;
      color:#93c5fd;
    }
  </style>
</head>
<body>

  <div class="container">

    <h1>Dynacademy</h1>

    <p>
      AI-Powered Education & Career Guidance Platform helping learners
      with career guidance, APS calculations, university matching,
      study assistance, bursary support, and wellness tracking.
    </p>

    <a href="https://dynacademy.base44.app" class="btn" target="_blank">
      Launch Platform
    </a>

    <div class="features">

      <div class="card">
        <h3>AI Career Guidance</h3>
        <p>Get personalized career recommendations based on interests and subjects.</p>
      </div>

      <div class="card">
        <h3>APS Calculator</h3>
        <p>Automatically calculate APS scores and university eligibility.</p>
      </div>

      <div class="card">
        <h3>AI Study Assistant</h3>
        <p>Generate summaries, quizzes, and study plans using AI.</p>
      </div>

      <div class="card">
        <h3>Bursary Finder</h3>
        <p>Discover bursary opportunities suited to your academic profile.</p>
      </div>

    </div>

  </div>

</body>
</html>

```bash
git clone https://github.com/yourusername/dynacademy.git

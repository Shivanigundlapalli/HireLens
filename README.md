#  HireLens AI — Smart Resume Intelligence Platform

> “Stop guessing. Start hiring smart — with HireLens.”

---

##  Overview

**HireLens AI** is an **AI-powered Resume Intelligence Platform** that transforms the hiring process for both **recruiters** and **job seekers**.  
It uses advanced AI models (GPT-4 / Gemini) to evaluate resumes, validate authenticity, detect fraud, and generate smart insights like skill gaps, personality traits, and career growth predictions.

HireLens bridges the gap between **manual recruitment** and **AI-driven talent analysis**, making hiring faster, fairer, and smarter.

---

##  Core Features

###  For Job Seekers
-  **Smart Resume Analyzer:** Get instant feedback on strengths, weaknesses, and overall ATS score.
-  **Skill Gap Detection:** Find missing skills for your target job roles.
-  **Career Path Predictor:** Suggests ideal next career roles based on your profile.
-  **Salary Estimation:** AI-predicted salary range based on your experience and skills.
-  **Resume Authenticity Check:** Detects fake or exaggerated data using pattern analysis.
-  **ATS Compatibility Checker:** Ensures your resume passes Applicant Tracking Systems.
-  **Smart Resume Builder:** Build an ATS-optimized resume using AI prompts and templates.

###  For Recruiters
- **Bulk Resume Uploads:** Upload and analyze multiple resumes simultaneously.
-  **Live Resume Preview:** View documents before analysis with smooth UI.
-  **AI-Powered Matching:** Match resumes to job descriptions with fit scores.
-  **Authenticity Validator:** Cross-checks education, timelines, and credibility.
-  **Fraud Detection Engine:** Flags copied or unrealistic resume claims.
-  **Recruiter Dashboard:** Displays ranked candidates with Fit %, key strengths, and weaknesses.
-  **Culture Fit Predictor:** Uses NLP to assess personality compatibility.

###  AI Chatbot Assistant — *HireBot*
- Positioned at bottom-right of the site.
- Offers interactive help for recruiters and job seekers.
- Explains ATS results, resume feedback, and navigation.
- Powered by GPT-based conversational AI.
- Speaks in a professional, human-like tone.
- Available 24/7 to enhance user experience.

---

##  How It Works
1. **Upload Resume (PDF/DOCX)** — Job seeker or recruiter uploads resumes.
2. **AI Parsing & Analysis** — Extracts text and evaluates data authenticity.
3. **AI Scoring** — Generates ATS, Fit, and Career Prediction scores.
4. **Dashboard Visualization** — Displays results, insights, and recommendations.
5. **Chatbot Support** — Provides on-page guidance using natural conversation.

---

## Tech Stack

**Frontend:** React.js, Tailwind CSS, Framer Motion  
**Backend:** Node.js, Express.js  
**Database:** MongoDB / Firebase  
**AI Models:** OpenAI GPT-4 / Gemini Pro  
**Resume Parsing:** pdf.js, docx-parser  
**Hosting:** Vercel (Frontend) / Render or Railway (Backend)

---

##  Design & UX

- Minimal, professional interface with blue-accent theme.  
- Responsive design for desktop and mobile.  
- Recruiter and Job Seeker flows are separated for clarity.  
- Integrated chatbot for real-time AI support.  
- Smooth animations (Framer Motion) for modern interaction.  

---

##  Unique Features

-  Real-time **Resume Verification Badge** for authentic profiles.  
-  **Fraud Detection Engine** to flag fake data.  
-  **Fit Score Ranking** system for recruiter dashboards.  
-  **AI Chat Assistant** powered by GPT for instant help.  
- **Visual Analytics Dashboard** for recruiters to view trends and insights.  
-  **Career Predictor** for job seekers powered by NLP and data modeling.  

---

## Installation & Setup

```bash
# Clone repository
git clone https://github.com/your-username/HireLens-AI.git

# Navigate to folder
cd HireLens-AI

# Install dependencies
npm install

# Add your environment variables in .env file
OPENAI_API_KEY=your_api_key_here
GEMINI_API_KEY=your_gemini_key_here

# Run app
npm start

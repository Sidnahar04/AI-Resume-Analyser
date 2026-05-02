# AI Resume Analyzer 🚀

An AI-powered Resume Analyzer and Job Matcher built using React.js, Node.js, Express, and AI APIs.  
This application helps users compare their resume against a job description and receive an ATS-style match score, missing skills analysis, strengths, and improvement suggestions.

---

# ✨ Features

- 📄 Upload Resume (.docx supported)
- 🤖 AI-based Resume vs Job Description analysis
- 📊 ATS Match Score
- ✅ Strengths Identification
- ❌ Missing Skills Detection
- 💡 Resume Improvement Suggestions
- ⚡ Fast and responsive UI
- 💾 Session Storage support (No database required)

---

# 🛠️ Tech Stack

## Frontend
- React.js
- Axios
- CSS3

## Backend
- Node.js
- Express.js
- Multer
- Mammoth (.docx parser)

## AI Integration
- OpenAI API / OpenRouter API

---

# 📂 Project Structure

```bash
resume-analyzer/
│
├── client/
│   ├── src/
│   │   ├── App.js
│   │   ├── App.css
│   │   └── index.js
│   │
│   └── package.json
│
├── server/
│   ├── index.js
│   ├── .env
│   └── package.json
│
└── README.md

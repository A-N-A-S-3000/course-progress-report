# 📊 Course Progress Report Generator

A simple Flask web app that allows users to fill in course information and download a structured Word document report. This app is ideal for training programs, workshops, and academies to summarize course content, outcomes, and activities.

🌐 Live Demo: [course-progress-report.onrender.com](https://course-progress-report.onrender.com)

---

## 🚀 Features

- Course creation form with:
  - Path selection (AI, Data Science, AI in IoT)
  - Course name and description
  - Dynamic course highlights and topics
  - Required and optional learning outcomes
  - Activities and more
- Live word counter for course description
- PDF and Word document generation
- Automatically downloads a formatted `.docx` report
- Deployed using **Render** (Free Tier)

---

## 🧑‍💻 Tech Stack

- **Backend:** Flask (Python)
- **Frontend:** HTML, CSS, JavaScript
- **Document Export:** `python-docx`, `pdfkit`, `weasyprint`
- **Deployment:** [Render.com](https://render.com)


---

## 📦 Installation

```bash
git clone https://github.com/YOUR-USERNAME/course-progress-report.git
cd course-progress-report
python -m venv venv
source venv/bin/activate   # or venv\\Scripts\\activate on Windows
pip install -r requirements.txt

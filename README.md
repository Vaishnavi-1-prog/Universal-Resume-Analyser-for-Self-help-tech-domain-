# 📄 Universal Resume Analyzer – AI Career Report Generator

A smart, multi-domain resume analyzer that reads any uploaded PDF resume and provides:

✅ Accurate name, education, work experience  
✅ Detected skills from known job markets  
✅ Career readiness scoring vs real-world job roles  
✅ Personalized learning roadmap (Coursera, NPTEL, Google)  
✅ Next-step career tips (based on domain)  
✅ Auto-generated PDF career report  
❌ No irrelevant summary or assumptions

---

## 🚀 Features

- 🔍 **Smart Name Detection** – Extracts candidate name using visual size and top position
- 🎓 **Education Extractor** – Captures only college/university + degrees
- 🧠 **Experience Filter** – Pulls real job/internship entries with date-based filtering (e.g., `2022–Present`)
- 🧰 **Skills Scanner** – Detects skills from 8+ domains: Tech, HR, Law, Medicine, Teaching, Marketing, etc.
- 💼 **Role Matching Engine** – Compares resume with real job descriptions using TF-IDF + Cosine Similarity
- 📘 **Course Recommendations** – Shows missing skill courses from trusted providers
- 🧭 **Next Step Career Advice** – Custom career tips per domain
- 📎 **PDF Report Generator** – Auto-generates & downloads a complete career readiness report

---

## 💡 Supported Domains

- 📊 Data / Business / ML / Cloud  
- 🏥 Healthcare / Medical  
- 🎓 Education / Teaching  
- 📢 Marketing / Content Writing  
- 👩‍💼 HR / Management
- but mostly tech line
---

## 🛠 How to Use

1. Open the project in **Google Colab**  
2. Upload your resume (PDF only)  
3. The tool will process it and generate:  
   - Candidate profile  
   - Matching roles + % score  
   - Learning roadmap  
   - Career tips  
   - Final PDF report download  

---

## 📦 Requirements

All dependencies are installed automatically inside Colab:
```bash
pip install PyMuPDF fpdf scikit-learn

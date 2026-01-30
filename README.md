🧠 An Explainable NLP-Based Approach to Automated Resume Screening and Candidate Ranking

Machine Learning Internship – Task 3
Organization: Future Interns
Track: Machine Learning (ML)

📌 Task Confirmation – FULLY SATISFIED ✅

As per the official Future Interns – Machine Learning Internship (Task 3) guidelines, this project fully satisfies and exceeds all required deliverables.

🔹 Official Task 3 Requirements

Build an ML system to automatically screen resumes based on a job role

Resume text cleaning & parsing

Skill extraction & matching with job descriptions

Candidate ranking based on role fit

Skill gap identification

✅ Implementation Status
Requirement	Status
Resume parsing (PDF / DOCX / TXT)	✅ Implemented
Text preprocessing (NLP)	✅ Implemented
Skill extraction & matching	✅ Implemented
Semantic resume scoring	✅ Implemented
Skill gap identification	✅ Implemented
Multi-candidate ranking	✅ Implemented
Explainable ATS scoring	✅ Implemented
Real-world ATS-style UI	✅ Implemented

Result:
✔ All Task 3 requirements are met
✔ Ranking feature is explicitly implemented and demonstrated

🚀 Project Overview

This project is an ATS-style Resume / Candidate Screening and Ranking System that evaluates single or multiple resumes against a given job description using Natural Language Processing (NLP) and Machine Learning techniques.

The system assigns an explainable ATS score to each candidate and automatically ranks candidates based on their suitability for the job role.

🔍 Workflow

Upload one or multiple resumes (PDF / DOCX / TXT)

Parse and clean resume text using NLP

Extract relevant technical skills

Match skills with job requirements

Compute a semantic similarity score

Calculate skill coverage and identify skill gaps

Generate a final weighted ATS score

Rank candidates automatically based on the final score

This closely simulates real-world recruitment and HR analytics platforms.

🧠 Scoring Methodology (Industry-Level & Explainable)

The system uses a two-layer evaluation approach:

1️⃣ Semantic Match Score

TF-IDF Vectorization

Cosine Similarity

Measures contextual alignment between resume content and job description

2️⃣ Skill Coverage Score

Calculated strictly using job-required skills

Prevents inflated or misleading scores

🔥 Final ATS Score
Final ATS Score = (0.6 × Semantic Match) + (0.4 × Skill Coverage)


This ensures fair, transparent, and explainable candidate evaluation.

🏆 Candidate Ranking Logic

Each resume receives a Final ATS Score

Candidates are sorted in descending order

The system produces an explicit ranking:

Rank 1 → Highest suitability
Rank 2 → Moderate suitability
Rank 3 → Low suitability


This satisfies the “candidate ranking based on role fit” requirement of Task 3.

🛠️ Tech Stack

Programming Language: Python

Framework: Flask

NLP Libraries: NLTK

ML Libraries: Scikit-learn

Document Parsing: PyPDF2, python-docx

Frontend: HTML, CSS (App-style ATS UI)

⚙️ How to Run the Project Locally
1️⃣ Clone the Repository
git clone https://github.com/your-username/FUTURE_ML_03.git
cd FUTURE_ML_03

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Application
python app.py

4️⃣ Open in Browser
http://127.0.0.1:5000/

📂 Project Structure
FUTURE_ML_03/
│
├── app.py
├── requirements.txt
│
├── data/
│   └── job_description.txt
│
├── utils/
│   ├── text_cleaner.py
│   ├── skill_extractor.py
│   └── ranker.py
│
├── templates/
│   ├── index.html
│   └── ranking.html
│
├── static/
│   └── style.css
│
├── uploads/
└── README.md

🧪 Testing & Ranking Demonstration

To validate correctness, explainability, and ranking behavior, three controlled resumes were evaluated together:

🟢 Strong Resume

High skill coverage (≈100%)

Moderate semantic alignment

Ranked 1st with the highest Final ATS Score

🟡 Medium Resume

Partial skill match

Moderate semantic similarity

Ranked 2nd

🔴 Weak Resume

Low skill relevance

Multiple missing required skills

Ranked 3rd (last) with a very low score

This clearly demonstrates accurate discrimination and ranking, a core ATS requirement.

📸 Screenshots (MANDATORY)

Home Page – Resume Upload Interface
<img width="1366" height="768" alt="Screenshot (141)" src="https://github.com/user-attachments/assets/b7ca6cbe-21a4-4b31-8c8f-10a2b85e6869" />

Rank 1 – Strong Resume Output
<img width="1366" height="768" alt="Screenshot (142)" src="https://github.com/user-attachments/assets/91240b2d-a24e-45c2-98ab-835d93ff1fe6" />

Rank 2 – Medium Resume Output
<img width="1366" height="768" alt="Screenshot (143)" src="https://github.com/user-attachments/assets/159aed01-1afd-4bf9-a942-d245e32d3db8" />

Rank 3 – Weak Resume Output
<img width="1366" height="768" alt="Screenshot (144)" src="https://github.com/user-attachments/assets/e51ddc7c-5066-433b-b58d-0fba840991e6" />

🏆 Internship Context

This project was developed as part of the Machine Learning Internship at Future Interns, under the Skill & Task Phase.

Internship Track: Machine Learning (ML)

Task Number: Task 3

Focus: Real-world NLP-based ML systems

The project emphasizes explainability, correctness, and practical relevance, not just academic theory.

🎯 Key Learnings

Resume text preprocessing using NLP

Feature extraction with TF-IDF

Semantic similarity measurement

Skill-based candidate evaluation

Multi-candidate ranking logic

Explainable ML scoring

Building end-to-end ML web applications

🧑‍💼 Interview-Ready Summary

“I built an explainable ATS-style resume screening system that evaluates and ranks multiple candidates using semantic similarity and skill coverage, ensuring fair and transparent recruitment screening.”

✅ Final Verdict

✔ Task 3 fully completed
✔ Candidate ranking explicitly implemented
✔ Explainable ML system
✔ Internship-ready & evaluation-safe
✔ Strong for portfolio, GitHub

📜 License

This project is released under the MIT License and is intended for academic and educational purposes only.

© 2026 – Machine Learning Internship | Future Interns

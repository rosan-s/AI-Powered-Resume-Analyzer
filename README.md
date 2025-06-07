🚀 AI-Powered Resume Analyzer
AI-Powered Resume Analyzer is a smart virtual HR assistant that uses Google Gemini AI to analyze resumes, identify strengths and weaknesses, and assess job fit based on descriptions. It helps both job seekers and recruiters make more informed decisions in the hiring process.

📌 Features
📄 General Resume Analysis
Summarizes the resume in one line.

Lists current skill sets.

Detects skill gaps and recommends improvements.

Suggests online courses to enhance skills.

Highlights strengths and weaknesses with professional insights.

📑 Resume & Job Description Matching
Compares resume with a specific job description.

Calculates a compatibility score.

Identifies missing skills required for the job.

Recommends if the resume is job-ready or needs updates.

🧠 How It Works
Resume Upload & Parsing

Extracts text using pdfplumber.

Falls back to OCR (pytesseract) for scanned PDFs.

AI-Powered Analysis

Sends resume data (and optional job description) to Google Gemini AI.

Uses a dynamic prompt to generate professional evaluations.

Feedback & Suggestions

Gemini AI evaluates skills, offers improvement tips, and recommends relevant courses.

Optional job-match comparison provides additional insight.

🛠 Tech Stack
Component	Technology
Frontend	Streamlit
Backend	Python
AI Model	Google Gemini AI
PDF Parsing	pdfplumber
OCR Fallback	pytesseract, pdf2image
Environment	.env file for API key security

🧪 Requirements
Install dependencies using the included requirements.txt:

bash
Copy
Edit
pip install -r requirements.txt
🔐 Setup
Clone the repository.

Add your Google Generative AI API key in a .env file:

ini
Copy
Edit
GOOGLE_API_KEY=your_api_key_here
Run the application:

bash
Copy
Edit
streamlit run app.py
📁 Project Structure
bash
Copy
Edit
.
├── app.py                # Streamlit app entry point
├── resume_analyzer.ipynb# Optional Jupyter notebook for testing
├── requirements.txt      # Dependency list
├── .env                  # Environment variables (API key)
├── uploaded_resume.pdf   # Sample resume for testing
🧑‍💻 Developer
Developed by Rosan S
📧 roshandharan00@gmail.com
🔗 LinkedIn

🤝 Contributions
Contributions are welcome!

Fork the repository

Create a new branch

Submit a pull request with detailed information about your changes

🏁 License
This project is for educational and professional demonstration purposes.


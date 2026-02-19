#  AI-Based Resume Screening System (Including Non-ATS Resumes)

An intelligent resume screening system that evaluates resumes using Generative AI (OpenAI GPT API) and OCR technology.  
This system can analyze both normal and scanned (non-ATS) resumes using AI.



##  Features

  -Supports multiple resume formats:
  - `.docx`
  - `.txt`
  - Scanned images (`.png`, `.jpg`)
  -OCR-based text extraction using Tesseract
  -GPT-powered resume evaluation with OpenAI API
  -AI-generated:
  - Match Score (0–100)
  - Key Strengths
  - Missing Skills
  - Hiring Recommendation
  -Web UI using Gradio



##  Technologies Used

- Python
- Gradio
- OpenAI GPT API (Generative AI)
- Tesseract OCR
- docx2txt
- Pandas


##  How It Works

1. Enter the job description
2. Upload resumes (DOCX/TXT/Image)
3. Extract text using OCR if needed
4. Send text to GPT model
5. Receive AI-generated match score and recommendation
6. Display results in a table


##  Installation

###  Clone the Repository

```bash
git clone https://github.com/AnanthS-18/Ai-based-resume-screening-even-non-ATS-resume-GENAI.git
cd Ai-based-resume-screening-even-non-ATS-resume-GENAI

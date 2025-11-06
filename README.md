# AI Cover Letter Generator

A desktop application that generates tailored cover letters by combining a user’s resume and a job description using OpenAI’s GPT-4 model. The app features a simple GUI, supports multiple file formats, and exports cover letters in DOCX and PDF formats. It is packaged as a standalone macOS application for easy distribution. So far, it has several users and has sped up the application process of 1,000+ job applications, saving hours of time.

---

## Features

- **AI-Powered Generation**  
  Uses GPT-4 to generate personalized, professional cover letters based on the user’s resume and a pasted job description.

- **Resume File Parsing**  
  Extracts text content from PDF, DOCX, and TXT resume files for use in prompts.

- **GUI Interface**  
  Built with Tkinter, allowing users to upload a resume, paste a job description, generate a cover letter, and export results with a few clicks.

- **PDF and DOCX Export**  
  Supports exporting generated cover letters as well-formatted PDF (ReportLab) or DOCX (python-docx) files.

- **Standalone macOS Application**  
  Bundled with PyInstaller, enabling users to launch the application without requiring a Python environment or command line.

---

## Tech Stack

- **Python**  
- **Tkinter** – GUI framework  
- **LangChain + OpenAI API** – LLM integration  
- **PyPDF2, python-docx** – Resume parsing  
- **ReportLab** – PDF export  
- **dotenv** – API key management  
- **PyInstaller** – Application bundling

---
Usage:
<img width="809" height="639" alt="image" src="https://github.com/user-attachments/assets/c0343d31-50ba-4415-a720-6ccc23475b65" />
<img width="1702" height="1107" alt="image" src="https://github.com/user-attachments/assets/e0a2ed7e-66e8-4ef7-afd5-d72b0ef993f6" />
<img width="1153" height="969" alt="image" src="https://github.com/user-attachments/assets/2cb02b19-5813-48c7-9983-c2f1e1105c68" />


## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/willzhou109/Cover-Letter-Generator.git
cd ai-cover-letter-generator

### 2. Create and Activate Virtual Environment
python3 -m venv venv
source venv/bin/activate  # macOS/Linux

### 3. Install Dependencies
pip install -r requirements.txt

### 4. Create .env file in the project root
OPENAI_API_KEY=your_api_key_here

### 5. RUnning the App
python main.py

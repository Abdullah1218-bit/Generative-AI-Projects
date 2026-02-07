# Generative AI Projects

A collection of small, focused generative-AI notebooks for chat, resume analysis, and web-scraping QA.

## Repository Structure

- Chatbot/
  - ChatBot.ipynb
  - LangChain_PDF_QA_Chatbot_Guide.pdf
- Resume Analyzer and Job Matcher/
  - Resume Analyzer and Job matcher.ipynb
  - job.txt
  - resume.txt
  - resume_1.docx
- WebScraper QA chatbot/
  - Web Scraper QA ChatBot.ipynb

## Prerequisites

- Python 3.9+ (recommended 3.10+)
- pip
- Jupyter Notebook or JupyterLab

## Setup (Step-by-Step)

1) Create and activate a virtual environment at the repo root:

```bash
python -m venv .venv
# Windows PowerShell
.\.venv\Scripts\Activate.ps1
```

2) Install Jupyter and common notebook tools:

```bash
pip install notebook ipykernel
```

3) Create environment files in each project folder:

- Copy `.env.example` to `.env` inside each folder and fill in your keys.
- Never commit `.env` to Git.

4) Launch Jupyter:

```bash
jupyter notebook
```

5) Open the notebook you want and run all cells top-to-bottom. If a module is missing, install it with pip and re-run the cell.

## Project Usage

### Chatbot

1) Open Chatbot/ChatBot.ipynb
2) Ensure Chatbot/.env is populated
3) Run all cells to initialize the chatbot workflow

### Resume Analyzer and Job Matcher

1) Open Resume Analyzer and Job Matcher/Resume Analyzer and Job matcher.ipynb
2) Ensure Resume Analyzer and Job Matcher/.env is populated
3) Use job.txt and resume.txt (or resume_1.docx) as sample inputs
4) Run all cells to evaluate and match resumes to job descriptions

### WebScraper QA chatbot

1) Open WebScraper QA chatbot/Web Scraper QA ChatBot.ipynb
2) Ensure WebScraper QA chatbot/.env is populated
3) Run all cells to scrape and ask questions over the retrieved content

## Security Notes

- `.env` files are excluded from Git to protect your API keys.
- Rotate any keys that were ever shared outside your machine.

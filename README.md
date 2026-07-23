# LLM Resume Evaluator

An AI-powered Resume Evaluator built using Python and the Groq API. It analyzes resumes against a job description and provides structured feedback, including ATS score, matching skills, missing keywords, strengths, and improvement suggestions.

## Features

- Resume parsing (PDF & DOCX)
- Job Description analysis
- ATS compatibility score
- Skill matching
- Missing keyword detection
- AI-generated feedback using Groq LLM
- Structured JSON output with Pydantic

## Tech Stack

- Python
- Groq API
- Pydantic
- python-dotenv
- PyPDF
- python-docx

## Installation

```bash
git clone the project using mu git project link.
cd LLM_RESUME_EVALUATOR_PROJECT

python -m venv .venv

# Windows
.venv\Scripts\activate

pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_api_key_here
```

## Run

```bash
python resume.py
```

## Project Structure

```
├── resume.py
├── requirements.txt
├── .env
├── README.md
└── sample_resume.pdf
```

## Future Improvements

- Streamlit Web UI
- Support for more resume formats
- Multiple LLM providers
- Resume ranking

## License

MIT License
# Resume-Ranker
Resume Ranker is a FastAPI-based application that automates the process of ranking resumes based on job descriptions. It uses Google's Generative AI SDK (Gemini) to extract ranking criteria from job descriptions and score resumes against those criteria. The application supports PDF and DOCX files and returns the results in a structured CSV format.

Extract Ranking Criteria:

Upload a job description (PDF or DOCX).
Extract key ranking criteria (e.g., skills, experience, certifications) using Google's Gemini model.
Score Resumes:

Upload multiple resumes (PDF or DOCX).
Score each resume against the extracted criteria.
Generate a CSV file with individual and total scores for each candidate.
User-Friendly API:

Built with FastAPI.
Includes Swagger UI for easy testing and documentation.

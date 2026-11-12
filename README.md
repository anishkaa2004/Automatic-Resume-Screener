# Automatic-Resume-Screener
Python based resume screening tool using keyword matching and weighted scoring
## Project Overview
The Automatic Resume Screener is a Python-based desktop application designed to simplify the initial resume screening process. It extracts text from PDF and TXT resumes, compares candidate profiles against job descriptions and required skills, and ranks candidates based on keyword matching and weighted scoring.

## Key Features
- **Resume Parsing:** Extracts text from PDF and TXT resume files.
- **Keyword Extraction:** Identifies relevant skills and keywords from resumes and job descriptions.
- **Weighted Scoring:** Assigns 75% weight to required skills and 25% to preferred skills.
- **Candidate Ranking:** Automatically ranks resumes according to their overall matching scores.
- **Match Analysis:** Displays matched required and preferred keywords.
- **CSV Export:** Allows users to export screening results for further analysis.
- **Desktop GUI:** Interactive graphical interface built using Tkinter.

## Technologies Used
- Python
- Tkinter
- PyPDF2
- CSV
- Regular Expressions

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Automatic-Resume-Screener.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Automatic-Resume-Screener
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   python resume_screener.py
   ```

## How It Works
1. Select multiple resumes in PDF or TXT format.
2. Enter the job description.
3. Specify required and preferred skills.
4. Click on Run Screening.
5. View candidates ranked by their overall matching scores.
6. Export the screening results into a CSV file.

## Scoring Methodology

The application calculates the matching percentage using:

- Required Skills Score: 75%
- Preferred Skills Score: 25%

**Final Score = (0.75 × Required Score) + (0.25 × Preferred Score)**

## Future Enhancements
- NLP-based resume analysis.
- Semantic skill matching.
- Resume categorization by job roles.
- Advanced candidate analytics.
- Web-based interface.

## Disclaimer
This project is intended for educational and demonstration purposes. Its keyword-based scoring should be used as an initial screening aid, not as an automated hiring decision.

## Author
Anishka Garg
## Application preview



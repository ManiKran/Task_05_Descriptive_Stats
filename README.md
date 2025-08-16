Task 05 – Descriptive Statistics using AI

📊 Project Overview

This project explores descriptive statistics on the 2025 Syracuse University Women’s Lacrosse team using AI tools like ChatGPT. The dataset was extracted from a publicly available PDF and manually structured for analysis. We extend the project with validation scripts to check AI-generated answers.

⸻

🧠 Objectives
	•	Extract structured data from a PDF sports stats sheet.
	•	Use ChatGPT to answer statistical questions about team and player performance.
	•	Validate AI-generated answers with Python using structured data.
	•	Generate reproducible prompts.md containing both questions and answers.
	•	Develop a narrative from the data for reporting or presentations.

⸻

📁 Repository Contents
	•	prompts.md – Contains all analysis questions and ChatGPT’s answers.
	•	Complex_Questions_and_Answers.docx – File with more complex Q&A generated via AI.
	•	Task_05_Data.pdf – Original dataset source.
	•	validator.py – Script to validate AI answers against the actual dataset.
	•	README.md – This file.

🚀 How to Use
	1.	Clone the repository:

```bash
git clone https://github.com/ManiKran/Task_05_Descriptive_Stats.git
cd Task_05_Descriptive_Stats
```
2.	Install dependencies:
   
```bash
pip install -r requirements.txt
```
3.	Run the validator to cross-check AI answers:
```bash
python validator.py
```

4.	Review outputs in the generated summary file comparing ChatGPT’s answers with actual calculations.

⸻

🔍 Summary of Findings
	•	Top Scorer: Emma Ward (57 goals)
	•	Most Assists: Emma Ward (34 assists)
	•	Most Draw Controls: Olivia Adamson (144)
	•	Highest Shooting %: Natalie Smith (51.3%)
	•	Highest SOG %: Emma Tyrrell (84.6%)
	•	Points Leader: Emma Ward (91 total points)

(See validator output for cross-checked results.)

✅ Status
	•	✅ Data Extraction
	•	✅ Question Answering with LLM
	•	✅ Prompt Engineering
	•	✅ Summary File (prompts.md)
	•	✅ Validator Script (validator.py)
	•	✅ README File



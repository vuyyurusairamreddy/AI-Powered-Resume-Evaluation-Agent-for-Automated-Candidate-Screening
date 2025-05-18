# AI-Powered-Resume-Evaluation-Agent-for-Automated-Candidate-Screening
An AI-powered Resume Evaluation Agent built on the n8n automation platform to streamline candidate screening. This tool parses resumes, matches them against job descriptions using AI (e.g., OpenAI), scores candidates, and automates communication — helping recruiters make faster, data-driven hiring decisions.
# 🤖 AI-Powered Resume Evaluation Agent using n8n

This repository contains a fully automated workflow built on **n8n** to evaluate candidate resumes using **AI** and streamline the screening process for a **Data Scientist** role.

## 📌 Project Overview

The AI-Powered Resume Evaluation Agent performs end-to-end automation for candidate shortlisting by:
- Pulling resumes from unread Gmail emails with attachments.
- Extracting text content from PDF resumes.
- Using OpenAI to analyze and score resumes based on specific criteria.
- Writing results (scores and details) to a connected Google Sheet.

## 🧠 Evaluation Criteria

Each resume is scored based on the following:
- **Relevant Work Experience (2.5 pts)**: Must have 3+ years in data science or related roles.
- **Skills (2.5 pts)**: Includes Python, SQL, Machine Learning, etc.
- **Relevant Projects (2.5 pts)**: Must showcase applied data science work.
- **Education (2.5 pts)**: Bachelor's, Master’s, or PhD in a related domain.

**Total Score: 10 points**

## 🔄 Workflow Components

- **Gmail Trigger**: Checks unread emails every hour with attachments.
- **Extract from File**: Extracts text from attached PDF resumes.
- **AI Agent (OpenAI)**: Evaluates the resume using a structured prompt.
- **Structured Output Parser**: Formats the AI output into JSON.
- **Google Sheets**: Appends the evaluation data into a Google Sheet.




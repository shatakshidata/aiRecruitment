# aiRecruitment : JD and Resume Relevance Scoring
Developed an AI-powered tool to automate the candidate sourcing process using LLM and ML models that saves 20+ hour for a client

This repository contains a tool to evaluate the relevance of resumes against job descriptions using machine learning techniques and APIs like OpenAI's GPT and Google Generative AI. The project aims to automate the resume-screening process by scoring resumes against job descriptions, providing a breakdown of the scores for better hiring decisions.

## Features

- **Resume and Job Description Processing**:
  - Extract text from `.docx`, `.pdf`, and `.url` files.
  - Pair job descriptions with resumes within a structured folder setup.

- **Relevance Scoring**:
  - Uses OpenAI GPT and Google Generative AI for scoring resumes against job descriptions.
  - Generates scores on a scale of 0–1 with detailed breakdowns.

- **Embedding and Similarity Analysis**:
  - Calculates embeddings using OpenAI and SBERT (Sentence-BERT).
  - Computes cosine similarity for a detailed comparison.

- **Visualization**:
  - Plots cosine distances for better interpretability.

- **Fine-Tuning**:
  - Custom weights for skills, experience, and education to refine scoring.

- **Dynamic Pair Generation**:
  - Creates positive and negative pairs of resumes and job descriptions for model training.

## Prerequisites

- Python 3.7+
- Google Colab (or a similar environment)
- APIs:
  - OpenAI API
  - Google Generative AI
- Libraries:
  - `pandas`
  - `matplotlib`
  - `sentence-transformers`
  - `tiktoken`
  - `PyPDF2`
  - `docx`



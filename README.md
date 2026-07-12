# Resume_Ranking
Overview
An AI-powered resume screening tool built to automate the initial stages of recruitment. The system extracts key information from candidate CVs, compares them against job descriptions, and ranks candidates based on relevance — giving actionable, explainable feedback for each match.
Key Features

Automated parsing and extraction of skills, experience, and qualifications from resumes
NLP-based semantic matching between CV content and job description requirements
Candidate ranking system based on similarity scores
Explainable AI feedback showing why a candidate scored the way they did (not just a black-box score)

Tech Stack

Language: Python
ML/NLP Frameworks: PyTorch, Scikit-learn
Models: DistilBERT, SBERT (Sentence-BERT) for semantic embedding and similarity scoring

How It Works

Resumes and job descriptions are preprocessed and cleaned (text normalization, tokenization).
SBERT/DistilBERT generate contextual embeddings for both the CV and job description.
Cosine similarity (or a similar metric) is used to score how well a candidate matches the role.
Candidates are ranked, and feedback is generated highlighting matched/missing skills.

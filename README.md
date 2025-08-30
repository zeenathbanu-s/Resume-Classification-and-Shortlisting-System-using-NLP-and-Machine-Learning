Resume Classification and Shortlisting System using NLP and Machine Learning
📌 Introduction

In today’s competitive job market, resume screening is time-consuming and prone to errors. HR teams often receive hundreds of resumes for a single job opening. Manually going through them is inefficient and may overlook strong candidates.

This project automates resume classification and shortlisting using Natural Language Processing (NLP) and Machine Learning (ML). It classifies resumes into predefined job categories and shortlists the most relevant ones for recruiters.

🎯 Objectives

Automatically classify resumes into job categories.

Apply NLP techniques for cleaning and transforming resume text.

Use ML models for classification and shortlisting.

Provide visualization of job categories and shortlisted resumes.

Export shortlisted resumes to a CSV file for HR usage.

⚙️ Methodology

Data Collection – Labeled resume dataset with job roles.

Data Preprocessing – Text cleaning, tokenization, TF-IDF vectorization.

Label Encoding – Converting job role labels into numerical values.

Model Training – K-Nearest Neighbors (KNN) classifier with One-vs-Rest framework.

Evaluation – Metrics: accuracy, precision, recall, F1-score.

Visualization – Graphs (bar charts, pie charts, confusion matrix).

Shortlisting Engine – Selects best-matching resumes for a chosen job role and exports results.

🏗️ System Architecture

User Interface – Allows HR staff to interact, select roles, and download shortlisted resumes.

Preprocessing Module – Cleans and vectorizes text.

Machine Learning Engine – Trains and predicts job categories.

Shortlisting Engine – Matches resumes with job roles and filters top candidates.

Visualization Module – Displays insights with graphs.

📊 Results

Successfully classified resumes into job roles with reasonable accuracy.

Visualized job role distributions using bar charts and pie charts.

Provided confusion matrix for model evaluation.

Allowed HR staff to shortlist candidates by job role and export to CSV.

✅ Conclusion

This system demonstrates how NLP and ML can automate resume screening. While KNN provided acceptable results, future improvements could use BERT or other deep learning models for better accuracy. The project reduces manual effort, speeds up recruitment, and helps HR teams focus on the most suitable candidates.

📚 References

A. Heakl, J. Smith, and R. Chen, ResumeAtlas: Revisiting Resume Classification, arXiv, 2024.

V. Paranthaman, S. Kumar, and L. Devi, Resume Screening Automation, IJMI, 2024.

Anonymous, Resume Recommendation System, Procedia CS, 2020.

Y. Gan, H. Liu, and T. Zhao, LLM Agents in Recruitment, arXiv, 2024.

A. Bhatia, M. Singh, and R. Sharma, Resume Parsing using BERT, arXiv, 2019.

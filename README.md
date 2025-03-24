# AI-Based Resume Ranking System  

## 📌 Overview  
This project is an **AI-powered resume ranking system** that automates the initial screening of job applicants. Using **Natural Language Processing (NLP)** and **cosine similarity**, the system compares candidate resumes with a given job description and ranks them based on relevance.  

## 🚀 Features  
- Extracts text from **PDF resumes**  
- Uses **TF-IDF Vectorization** for text processing  
- Calculates **cosine similarity** to rank resumes  
- Provides a **user-friendly interface** using **Streamlit**  
- Supports **multiple resume uploads** for batch processing  

## 🛠️ Technologies Used  
- **Python**  
- **Streamlit** (for UI)  
- **PyPDF2** (for extracting text from PDFs)  
- **Scikit-learn** (for NLP and cosine similarity)  
- **Pandas** (for data handling)  

## 📌 How It Works  
1. The user inputs a **job description**.  
2. Multiple **PDF resumes** are uploaded.  
3. The system extracts text from each resume.  
4. It computes **cosine similarity** between resumes and the job description.  
5. Resumes are **ranked based on relevance**, and results are displayed.  

## 🔧 Installation & Usage  
### 1️⃣ Clone the Repository  
git clone https://github.com/ArsenicAsh/resume-ranking-system.git
cd resume-ranking-system

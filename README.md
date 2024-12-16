# Resume Scoring with Cosine Similarity 🚀

Welcome to the **Resume Scoring with Cosine Similarity** project! This R-based tool helps you score resumes by comparing them to a job description, using **Cosine Similarity** to evaluate the match. It's perfect for quickly evaluating how well a resume aligns with specific job requirements.

---

## 🔑 Features

- **Resume Text Extraction**: Automatically extracts text from PDF resumes.
- **Text Preprocessing**: Cleans the text by removing stopwords, punctuation, and irrelevant content.
- **Cosine Similarity**: Calculates how closely a resume matches a job description based on a similarity score (0-100%).
- **Customizable Job Descriptions**: Easily update the job description with relevant keywords.
  
---

## 📋 Requirements

Before running the script, install the following R packages if they are not already installed:

```r
# Install necessary packages if not already installed
if (!require("textclean")) {
  install.packages("textclean")
  library(textclean)
}

if (!require("tm")) {
  install.packages("tm")
  library(tm)
}

if (!require("pdftools")) {
  install.packages("pdftools")
  library(pdftools)
}

if (!require("textTinyR")) {
  install.packages("textTinyR")
  library(textTinyR)
}
```
## 🚀 How to Use 

**Clone the Repository:**

First, clone this repository to your local machine using the following steps:

Install Git: Download and install Git from here if you don't have it already.

Clone the Repository: Open your terminal (Command Prompt or PowerShell) and run the following command:

```
git clone https://github.com/hk1105/Resume-scoring.git
```

This will create a local copy of the repository on your machine.

**Prepare Your Files:**

Update the job_description variable with the specific job requirements.

Place the resume PDF in the appropriate location and update the resume_file path.

**Run the Script:**

The script will read both the job description and the resume PDF.

It will clean the texts by removing stopwords, punctuation, numbers, and unnecessary characters.

Cosine similarity will be calculated between the job description and the cleaned resume.

**View the Output:**

The script will output a similarity score, reflecting how closely the resume matches the job description.

## 🚀 Conclusion

This **Resume Scoring with Cosine Similarity** tool is a powerful way to automatically evaluate how well a resume aligns with a job description. By leveraging the **Cosine Similarity** metric, it offers an efficient and customizable solution for both job seekers and recruiters. The tool's flexibility allows you to easily adjust the job description and fine-tune the scoring process, making it a versatile asset in any recruitment process.

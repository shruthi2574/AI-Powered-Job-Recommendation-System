# 🤖 AI-Powered Job Recommendation System

An intelligent recommendation engine that suggests the most suitable jobs based on your resume or manually entered skills using NLP and machine learning. It highlights your matching and missing skills and even recommends learning resources to boost your employability.

---

## 🔍 Features

- 📄 Upload your resume (PDF) or manually input skills  
- 🧠 Extracts and cleans keywords using NLP  
- 📊 Computes job relevance using cosine similarity  
- ✅ Highlights matching skills  
- ❌ Lists missing skills  
- 🌐 Suggests learning resource URLs for missing skills  
- 📈 Displays a match score for each recommended job  

---

## 🧰 Tech Stack

| Tool         | Purpose                        |
|--------------|--------------------------------|
| Python       | Core language                  |
| Pandas       | Data handling                  |
| Scikit-learn | Cosine similarity (TF-IDF)     |
| NLTK / spaCy | Keyword extraction             |
| PyMuPDF      | Resume text extraction         |
| Google Colab | Cloud execution (no setup)     |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x (for local execution)
- Google Colab (recommended for ease)
- Resume in `.pdf` format or a list of skills

---

### ✅ Option 1: Run on Google Colab

1. Install required libraries:

   ```bash
   !pip install nltk
   !pip install PyMuPDF
   !pip install scikit-learn
   !pip install pandas
   ```

2.Upload your resume or enter your skills manually:

   ```bash
from google.colab import files
uploaded = files.upload()
   ```

3. Use the job dataset (CSV or predefined list).
4. Run the script and view results.

---
💻 Option 2: Run Locally
1.Clone the repository:

   ```bash
  git clone https://github.com/your-username/job-recommendation-system.git
cd job-recommendation-system

   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Script:

   ```bash
   python job_recommender.py
   ```

---

## 💡 Example Output


```
✅ Input Skills: python, sql, data analysis, machine learning

📋 Recommended Jobs:
------------------------
1. 🧑‍💼 Job: Data Analyst  
   🎯 Match Score: 91.3%  
   ✅ Matching Skills: python, sql, data analysis  
   ❌ Missing Skills: tableau, excel  
   📘 Learning Resources:  
   - tableau → https://www.coursera.org/learn/data-visualization-tableau  
   - excel → https://www.microsoft.com/en-us/learning/excel-skills.aspx  

------------------------
2. 🧑‍💼 Job: ML Engineer  
   🎯 Match Score: 88.1%  
   ✅ Matching Skills: python, machine learning  
   ❌ Missing Skills: docker, deep learning  
   📘 Learning Resources:  
   - docker → https://docs.docker.com/get-started/  
   - deep learning → https://www.deeplearning.ai  

------------------------
3. 🧑‍💼 Job: Data Scientist  
   🎯 Match Score: 85.7%  
   ✅ Matching Skills: python, sql, machine learning  
   ❌ Missing Skills: big data, cloud computing  
   📘 Learning Resources:  
   - big data → https://www.coursera.org/specializations/big-data  
   - cloud computing → https://cloud.google.com/learn  

---
```

## 📂 Project Structure

```
job-recommendation-system/
├── job_recommender.py
├── sample_jobs.csv
├── resume_parser.py
├── learning_resources.json
├── requirements.txt
└── README.md

```
```
---

## 🙋‍♀️ Author

**Gugulothu Shruthi**  
B.Tech,CSE—Narayanamma Institute of Technology  
✉️ [gugulothushruthi@gmail.com](mailto:gugulothushruthi@gmail.com)

---


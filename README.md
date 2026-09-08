<!-- ═══════════════════════════════════════════════════════
     ANAM SHEIKH — GitHub Profile README
     Repository: Anamshaikh2000
═══════════════════════════════════════════════════════ -->

<div align="center">

# 👋 Hi, I'm Anam Sheikh

### Associate Software Engineer · Java · Spring Boot · SQL · Generative AI

<p>
  <a href="https://linkedin.com/in/anam-sheikh-4b2239266">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/Anamshaikh2000">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="mailto:www.anamsheikh786@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://aws.amazon.com/certification/">
    <img src="https://img.shields.io/badge/AWS_Certified-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  </a>
</p>

</div>

---

## 👨‍💻 About Me

I'm an **Associate Software Engineer at Tech Mahindra** with hands-on experience in **Java, Spring Boot, SQL, Python, Generative AI and production troubleshooting**.

I enjoy building practical applications that combine traditional software engineering with AI — particularly **RAG systems, LLM-powered applications and Natural Language → SQL solutions**.

- 💼 Associate Software Engineer at **Tech Mahindra**
- 🌍 Working on an **international telecom project**
- 🛠️ Experience with **debugging, log analysis, root-cause analysis and code fixes**
- ☕ Focused on **Java, Spring Boot, SQL and backend development**
- 🤖 Building applications using **LLMs, RAG, LangChain, FAISS and Groq**
- 🔎 Interested in **AI-powered developer tools and automation**
- ☁️ **AWS Certified Cloud Practitioner**
- 🧠 Solved **100+ coding problems**
- 🎯 Currently strengthening **DSA, Backend Development, SQL and System Design**

---

# 🛠️ Tech Stack

### Languages

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### Backend & Web

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-005571?style=flat-square)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

### Databases

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

### Generative AI

![Generative AI](https://img.shields.io/badge/Generative_AI-FF6F00?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-8A2BE2?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-7B61FF?style=flat-square)

### Tools & Platforms

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white)

---

# 🚀 Featured Projects

## 🧠 SQLPilot — AI-Powered SQL Assistant

**Python · Streamlit · Groq API · SQLite · Pandas · pypdf**

> Natural Language → SQL → Database Execution → Results  
> PDF → SQL Analysis → Explanation → Corrected SQL

SQLPilot is an AI-powered SQL assistant that converts natural-language questions into SQL queries, executes them against dynamically created databases, and analyzes SQL queries extracted from PDF documents.

### ✨ Key Features

- 💬 Converts **natural-language questions into SQL queries**
- 🗄️ Dynamically parses **user-provided database schemas**
- 🔗 Supports **multiple tables and SQL JOIN operations**
- ⚡ Creates a temporary **in-memory SQLite database**
- 📊 Executes generated SQL and displays query results
- 📄 Extracts PDF content using **pypdf**
- 🔍 Reviews SQL queries using an LLM
- ✅ Identifies queries as **Correct / Wrong**
- 🧠 Provides explanations for incorrect queries
- 🛠️ Generates **corrected SQL queries**
- 📦 Uses structured **JSON responses** for SQL analysis
- 🔐 Keeps API credentials outside source code using environment variables
- 🌐 Version-controlled using **Git and GitHub**

### 🏗️ Architecture

```text
                  SQLPilot
                     │
          ┌──────────┴──────────┐
          │                     │
          ▼                     ▼
 Natural Language             PDF Upload
     Question                     │
          │                       ▼
          ▼                      pypdf
       Groq LLM                    │
          │                       ▼
          ▼                 Extracted Text
    Generated SQL                 │
          │                       ▼
          ▼                    Groq LLM
     Schema Parser                │
          │                       ▼
          ▼                  SQL Analysis
 Temporary SQLite DB              │
          │                       ▼
          ▼                  Corrected SQL
     Query Result

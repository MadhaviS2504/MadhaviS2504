# 👋 Hi, I'm Madhavi Surapuraju

<div align="center">

**AI/ML Engineer | GenAI Engineer | Full Stack Engineer**

*13+ years of production engineering experience across Banking & Healthcare*  
*Specialized in RAG, LLMs, Agentic AI, Computer Vision, MLOps & ML Deployment*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/madhavi-surapuraju)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MadhaviS2504)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:madhavis.2504@gmail.com)
[![AWS](https://img.shields.io/badge/AWS_Architect-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/certified-solutions-architect-associate/)

</div>

---

## 🚀 Featured AI/ML Projects

### 1️⃣ **Tourism Package Prediction — Production MLOps Pipeline** ⭐ **FEATURED**

**Repository:** [Tourism_MLOps_Pipeline](https://github.com/MadhaviS2504/Tourism_MLOps_Pipeline)

End-to-end production ML workflow demonstrating enterprise-grade MLOps practices: reproducible data pipelines, model benchmarking, experiment tracking, model registry, CI/CD automation, and containerized deployment.

**Key Achievements:**
- ✅ **Leakage-safe preprocessing** with stratified split and training-only statistics
- ✅ **Model comparison:** Decision Tree vs Random Forest vs XGBoost (GridSearchCV tuning)
- ✅ **Experiment tracking** with MLflow (parameters, metrics, artifacts)
- ✅ **Model registry** on Hugging Face Hub for reproducible consumption
- ✅ **Containerized inference** with Streamlit UI and Docker
- ✅ **GitHub Actions CI/CD** for automated data prep → training → deployment pipeline

| Metric | Tech Stack |
|--------|-----------|
| **Language** | Python | pandas | scikit-learn | XGBoost |
| **MLOps** | MLflow | Hugging Face Hub | joblib |
| **Deployment** | Docker | Streamlit | GitHub Actions |

---

### 2️⃣ **Medical Assistant — Grounded RAG over 4,114-Page Medical Reference**

**Repository:** [Natural-Language-Processing-with-Generative-AI-RAG-Project](https://github.com/MadhaviS2504/Natural-Language-Processing-with-Generative-AI-RAG-Project)

Source-grounded medical knowledge assistant using RAG for evidence-based healthcare Q&A. Designed to support—not replace—clinical assessment through grounded generation and hallucination reduction.

**Key Achievements:**
- ✅ **Document ingestion:** 4,114-page medical reference processed with PyMuPDF
- ✅ **Token-aware chunking:** 8,492 retrieval-ready segments (512-token windows, 20-token overlap)
- ✅ **Semantic embeddings:** thenlper/gte-large (1,024-dim) stored in ChromaDB
- ✅ **Retrieval augmentation:** Top-3 relevant passages for context-grounded generation
- ✅ **LLM integration:** Mistral-7B via llama.cpp with GPU optimization & 5K-token context window
- ✅ **Safety & evaluation:** Context-only prompting + LLM-as-a-Judge (5/5 groundedness, 4–5/5 relevance)

| Metric | Tech Stack |
|--------|-----------|
| **RAG Pipeline** | LangChain | PyMuPDF | tiktoken | ChromaDB |
| **Embeddings** | Sentence-Transformers | thenlper/gte-large |
| **LLM** | Mistral-7B | llama.cpp | Hugging Face Hub |
| **Evaluation** | LLM-as-a-Judge | Prompt Engineering | Grounding Metrics |

---

### 3️⃣ **Pneumonia Detection — Transfer Learning & Computer Vision**

**Repository:** [Introduction-to-Neural-Networks](https://github.com/MadhaviS2504/Introduction-to-Neural-Networks)

Medical imaging AI for chest X-ray classification (pneumonia detection) using DICOM preprocessing, custom CNNs, and transfer learning. REST API + Streamlit UI for clinical decision support.

**Key Achievements:**
- ✅ **DICOM preprocessing:** pydicom + OpenCV for image normalization & augmentation
- ✅ **Model architecture:** Custom CNN vs VGG16, ResNet50, InceptionV3 transfer learning
- ✅ **Best model:** Fine-tuned InceptionV3 (80.98% accuracy, 0.8266 ROC-AUC, 64% recall)
- ✅ **Production API:** Flask REST endpoint for inference
- ✅ **Interactive UI:** Streamlit DICOM uploader for clinician workflows
- ✅ **Hub deployment:** Published model & app on Hugging Face Spaces

| Metric | Value | Tech Stack |
|--------|-------|-----------|
| **Test Accuracy** | 80.98% | TensorFlow/Keras |
| **ROC-AUC** | 0.8266 | Transfer Learning |
| **Recall** | 0.6402 | InceptionV3 |
| **Deployment** | Flask + Streamlit + Docker | Hugging Face |

---

### 4️⃣ **NewsFindr — Agentic AI with Multi-Tool Orchestration & SQL Safety**

Intelligent news aggregation system using ReAct agents, tool calling, SQL guardrails, and response caching. Retrieves credible sources, filters low-authority content, and summarizes personalized insights.

**Key Achievements:**
- ✅ **4-tool ReAct agent:** Query expansion → Web search (DuckDuckGo) → Credibility filter → Summarization
- ✅ **SQL safety:** Read-only agent with DML prohibition; tested against INSERT/UPDATE/DELETE injection
- ✅ **Dual-LLM architecture:** Groq llama-3.3-70b (deterministic reasoning) + gpt-oss-120b (generation)
- ✅ **Resilience:** SQLite response cache + retry-with-backoff for HTTP 429 rate limits
- ✅ **Results:** 9 raw results → 3–6 vetted sources per persona; high-credibility sources retained

| Component | Tech |
|-----------|------|
| **Agentic Framework** | LangChain | LangChain Agents | ReAct |
| **LLM Provider** | Groq (llama-3.3-70b-versatile) |
| **Tool Safety** | SQL Agent | DML Guards | Pydantic validation |
| **Resilience** | SQLite cache | Retry logic | Rate-limit handling |

---

## 📊 Technical Skills & Expertise

### 🤖 **AI/ML & Deep Learning**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-003366?style=flat-square&logo=xgboost&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Competencies:**
- Supervised learning: Decision Trees, Random Forests, XGBoost, SVM
- Deep learning: CNNs, transfer learning (VGG, ResNet, Inception), fine-tuning
- Computer vision: DICOM, medical imaging, image preprocessing & augmentation
- Evaluation: ROC-AUC, precision, recall, F1, cross-validation, class imbalance handling

### 🧠 **Generative AI & LLMs**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-004B8D?style=flat-square&logo=chromadb&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/LLMs-412991?style=flat-square&logo=openai&logoColor=white)

**Competencies:**
- **RAG systems:** Token-aware chunking, embeddings, vector retrieval, grounded generation
- **LLM evaluation:** LLM-as-a-Judge, groundedness scoring, relevance metrics
- **Agentic AI:** ReAct workflows, multi-tool orchestration, SQL agents, function calling
- **LLM ops:** Prompt engineering, context constraints, response caching, guardrails
- **Models & Embeddings:** Mistral-7B, Groq, Llama, Sentence Transformers, thenlper/gte-large

### 🔧 **MLOps, Cloud & Deployment**
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub%20Actions](https://img.shields.io/badge/GitHub%20Actions-2088F0?style=flat-square&logo=github-actions&logoColor=white)

**Competencies:**
- **MLOps:** MLflow experiment tracking & model registry, reproducible pipelines, versioning
- **Cloud:** AWS (Certified Solutions Architect), infrastructure, model hosting
- **Containerization:** Docker, Kubernetes, registry management
- **CI/CD:** GitHub Actions, Jenkins, automated testing, deployment pipelines
- **Inference:** Streamlit, Flask, REST APIs, model serving, Hugging Face Hub/Spaces

### 💻 **Backend & Full-Stack**
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)
![Spring%20Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**Competencies:**
- **Frameworks:** Spring Boot, REST APIs, JDBC, Spring Data JPA
- **Databases:** SQL Server, Oracle, MySQL, MongoDB, SQLite
- **API Design:** REST, Pydantic validation, error handling
- **Full-stack:** Angular, React, TypeScript, HTML5, CSS3 (secondary focus)

---

## 💼 Professional Experience

### **JPMorganChase — Software Engineer III / Senior Software Engineer**
*Aug 2022 – Present | Hyderabad, India*

- **Impact:** Contribute to firmwide data processing and publishing services for global financial platform operating in 100+ countries
- **Delivery:** Translate requirements into production-grade Java/Spring Boot APIs and SQL workflows
- **Scale:** Build and maintain high-volume data services ensuring integrity, reliability, and operational stability
- **Quality:** Author unit/integration tests; leverage GitHub Copilot for test generation while maintaining peer-review standards
- **Release:** Manage changes through GitHub Actions CI/CD pipelines and Change Request workflows
- **Support:** Diagnose and resolve critical production incidents with root-cause analysis under tight SLAs

**Tech:** Java 8+ | Spring Boot | REST APIs | Liquibase | SQL Server | Oracle SQL | GitHub Actions | CI/CD

---

### **Tata Consultancy Services (TCS) — Associate Consultant / IT Analyst**
*Apr 2016 – Aug 2022*

#### **Project: Clinics Without Walls (CWOW) — DaVita Inc.**
*Healthcare | Kidney Dialysis Platform | Nov 2018 – Aug 2022*

- Delivered healthcare features using Java 8, Spring Boot, Angular 7, TypeScript, Bootstrap in Agile model
- Owned **Labs Management and PMT modules** end-to-end with strong release quality
- Authored low-level and high-level design documents; collaborated with clinical stakeholders
- Mentored new team members on Angular architecture and CWOW patterns

#### **Project: Product Maintenance — McKesson Corporation**
*Healthcare | Pharmaceutical Distribution | Apr 2016 – Nov 2018*

- Developed Product Maintenance module for pharmaceutical item master (create, edit, copy operations)
- Built responsive UI using AngularJS, JavaScript, jQuery, HTML5, CSS3, Bootstrap
- Collaborated with business stakeholders to clarify requirements and validate workflows

### **Kantar GDC — Web Developer**
*Nov 2012 – Apr 2016 | Hyderabad, India*

- Developed web applications for market research platforms using AngularJS, HTML, CSS, JavaScript
- Built reusable, cross-browser-compatible components; contributed to UI standardization

---

## 🎓 Education & Certifications

### **Education**

| Degree | Institution | Timeline | Performance |
|--------|-------------|----------|-------------|
| **PGP in AI & Machine Learning** | Great Learning | Aug 2025 – Sep 2026 | **GPA: 4.25/5.0** |
| **Master of Computer Applications (MCA)** | University College for Women, Koti (Osmania University) | 2012 | **89.9%** |
| **B.Sc. (MECs)** | SSB Degree College (Sri Venkateswara University) | 2009 | **80.5%** |

**PGP Coursework:** Machine Learning | Deep Learning | Computer Vision | NLP with Generative AI | Advanced Generative AI for NLP | Advanced ML & MLOps | RAG and LLM Application Development

### **Certifications**

![AWS](https://img.shields.io/badge/AWS%20Certified%20Solutions%20Architect-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white) **Dec 2025**

![VSkills](https://img.shields.io/badge/VSkills%20Certified%20Angular%207%20Developer-3DDC84?style=for-the-badge) **Aug 2024**

---

## 🏆 Awards & Recognition

| Award | Year | Recognition |
|-------|------|-------------|
| 🥇 **Outstanding Performer of the Year** | 2019 | Exceptional performance and delivery excellence |
| 🤝 **Teammate of the Quarter** | 2021 | Outstanding collaboration and teamwork |
| 👥 **Best Team Award** | 2020 | Measurable application performance improvement |
| 🙌 **Applause Award** | 2018 | Effective client logistics management beyond scope |

---

## 📈 GitHub Profile Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=MadhaviS2504&theme=nord&show_icons=true&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=MadhaviS2504&theme=nord&layout=compact&hide_border=true)

</div>

---

## 🎯 Domain Expertise

| Domain | Experience | Highlights |
|--------|-----------|-----------|
| **Healthcare** | 6+ years | ESRD/Dialysis, Pharmaceutical Distribution, Medical AI/RAG, Clinical Decision Support |
| **Banking & Financial** | 4+ years | Firmwide data management, financial services platforms, 100+ countries |
| **AI/ML** | Current Focus | RAG, LLMs, Agentic AI, Computer Vision, MLOps, Production ML |

---

## 📱 Connect with Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/madhavi-surapuraju)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MadhaviS2504)
[![Email](https://img.shields.io/badge/madhavis.2504%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:madhavis.2504@gmail.com)

**📞 +91-9959578125**

</div>

---

## 🌍 Additional Information

| Attribute | Details |
|-----------|---------|
| **Location** | Hyderabad, India |
| **Languages** | English, Telugu |
| **Passport** | Valid |
| **Notice Period** | 60 Days |
| **Work Status** | Open to remote & relocation |

---

<div align="center">

### **"Building AI solutions that matter — from research to production."** ✨

**[⭐ Star my repositories](https://github.com/MadhaviS2504?tab=repositories) if you find my work interesting!**

*Last updated: October 2026*

</div>

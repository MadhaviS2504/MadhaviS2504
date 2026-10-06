# Madhavi Surapuraju — Professional Profile

**AI/ML Engineer | GenAI | Full Stack | 13+ Years Production Experience**

---

## 🎯 Executive Summary

Senior software engineer specializing in **production-grade AI/ML systems** with 13+ years of experience across **Banking and Healthcare**.

**Core Competencies:** RAG | LLMs | Agentic AI | Computer Vision | MLOps | Full-Stack Development | Production Deployment

**Current:** Senior Engineer at JPMorganChase  
**Education:** PGP AI & ML (4.25/5.0) | AWS Certified Architect | MCA

---

## 💼 Professional Positioning

### For Recruiters (LinkedIn)
I build production AI systems that deliver measurable business value. With 13+ years of engineering experience in banking and healthcare, plus specialized training in AI/ML, I can architect, develop, and ship enterprise-grade AI solutions—from data pipelines to deployed inference. My recent work spans RAG systems, LLM evaluation, agentic workflows, and MLOps automation.

**Current:** Maintaining high-volume data services at JPMorganChase for 100+ countries  
**Focus:** AI/ML engineering, GenAI application development, production ML deployment  
**Seeking:** AI/ML Engineer, ML Engineering Lead, GenAI Product Engineer roles

---

### For GitHub Portfolio
I deliver end-to-end AI/ML solutions with production discipline: data pipelines, model training, experiment tracking, containerization, and CI/CD automation. My projects demonstrate RAG, LLM evaluation, computer vision, and agentic AI architectures built for real-world use.

**[View Featured Projects](#featured-projects-1)**

---

## 🚀 Featured AI/ML Projects

### Project 1: Tourism Package Purchase Prediction — MLOps Pipeline ⭐
**Repository:** [Tourism_MLOps_Pipeline](https://github.com/MadhaviS2504/Tourism_MLOps_Pipeline)

**Problem:** Build a reusable ML pipeline for customer purchase prediction with production-grade practices.

**Solution:**
- Leakage-safe preprocessing (training-only imputation, stratified split)
- Model comparison: Decision Tree vs Random Forest vs XGBoost (GridSearchCV)
- Experiment tracking with MLflow (metrics, parameters, artifacts)
- Model registry on Hugging Face Hub
- Dockerized Streamlit inference app
- GitHub Actions CI/CD pipeline (automated data prep → training → deployment)

**Impact:** Demonstrates full MLOps lifecycle from raw data to containerized deployment

**Tech:** Python | pandas | scikit-learn | XGBoost | MLflow | Hugging Face | Docker | Streamlit | GitHub Actions

---

### Project 2: Medical Assistant — Grounded RAG Over 4,114-Page Medical Reference
**Repository:** [Natural-Language-Processing-with-Generative-AI-RAG-Project](https://github.com/MadhaviS2504/Natural-Language-Processing-with-Generative-AI-RAG-Project)

**Problem:** Build an evidence-based medical Q&A system that reduces hallucination and grounds answers in reliable sources.

**Solution:**
- Ingested and chunked 4,114-page medical reference into 8,492 retrieval-ready segments
- Generated 1,024-dimensional embeddings using thenlper/gte-large
- Stored embeddings in ChromaDB for efficient semantic search
- Retrieved top-3 passages to ground LLM generation
- Integrated Mistral-7B via llama.cpp with context constraints
- Built LLM-as-a-Judge evaluation pipeline (groundedness, relevance scoring)

**Impact:** Achieved 5/5 groundedness on medical queries; reduced hallucination risk through evidence grounding

**Tech:** Python | LangChain | PyMuPDF | ChromaDB | Sentence Transformers | Mistral-7B | llama.cpp | Hugging Face | LLM Evaluation

---

### Project 3: Pneumonia Detection — Transfer Learning & Computer Vision
**Repository:** [Introduction-to-Neural-Networks](https://github.com/MadhaviS2504/Introduction-to-Neural-Networks)

**Problem:** Develop a medical imaging classifier for chest X-ray pneumonia detection with high accuracy.

**Solution:**
- Processed DICOM images with pydicom and OpenCV
- Handled class imbalance with stratified splits and class weights
- Designed custom CNN and benchmarked VGG16, ResNet50, InceptionV3
- Fine-tuned InceptionV3 for optimal performance
- Deployed REST API (Flask) + interactive UI (Streamlit)
- Published model and app on Hugging Face Spaces

**Impact:** 80.98% accuracy | 0.8266 ROC-AUC | Production-ready inference API

**Tech:** Python | TensorFlow/Keras | CNN | Transfer Learning | pydicom | OpenCV | Flask | Streamlit | Docker | Hugging Face

---

### Project 4: NewsFindr — Agentic AI with SQL Safety & Resilience
**Problem:** Build an intelligent news aggregation agent that retrieves credible sources while maintaining safety and resilience.

**Solution:**
- 4-tool ReAct agent for query expansion, web search, credibility filtering, and summarization
- Read-only SQL agent with DML restrictions for safe database interactions
- Dual-LLM architecture: Groq (reasoning) + Generative LLM (text generation)
- SQLite response caching and retry-with-backoff for production resilience

**Impact:** Reduced 9 raw search results → 3–6 vetted sources; maintained high credibility

**Tech:** LangChain | Agents | ReAct | Groq | SQL Agent | SQLite | DuckDuckGo Search | Pydantic

---

## 🛠️ Technical Skills — Organized by Focus

### Tier 1: AI/ML & Deep Learning (Core Expertise)
**Machine Learning**
- Supervised learning: Classification, Decision Trees, Random Forest, XGBoost
- Evaluation metrics: ROC-AUC, precision, recall, F1, cross-validation
- Class imbalance handling, feature engineering, leakage prevention

**Deep Learning & Computer Vision**
- CNNs for image classification
- Transfer learning: VGG16, ResNet50, InceptionV3
- Medical imaging: DICOM processing, preprocessing, augmentation

**Generative AI & LLMs**
- RAG architecture: chunking, embeddings, retrieval, grounded generation
- LLM evaluation: LLM-as-a-Judge, groundedness scoring, relevance metrics
- Agentic AI: ReAct workflows, multi-tool orchestration, tool calling
- Prompt engineering, context constraints, hallucination reduction

### Tier 2: MLOps & Deployment (Production Excellence)
**Experiment Tracking & Model Registry**
- MLflow: experiment tracking, artifact management, model registry
- Hugging Face Hub: model versioning and distribution

**Containerization & Orchestration**
- Docker: image building, registry management, best practices
- Kubernetes: deployment, scaling, orchestration

**CI/CD & Automation**
- GitHub Actions: automated pipelines (data prep, training, deployment)
- Jenkins: legacy CI/CD systems

**Inference & API Delivery**
- Flask, Streamlit for REST APIs and interactive UIs
- Model serving and inference optimization

### Tier 3: Backend & Full-Stack (Foundational Strength)
**Backend Development**
- Java, Spring Boot, REST APIs
- JDBC, Spring Data JPA
- SQL Server, Oracle, MySQL, MongoDB

**Frontend (Secondary)**
- Angular 7, React, TypeScript
- HTML5, CSS3, Bootstrap

**Cloud & Infrastructure**
- AWS (EC2, S3, RDS, SageMaker)
- Docker, Kubernetes

---

## 💼 Professional Experience

### JPMorganChase — Senior Software Engineer III
**Aug 2022 – Present | Hyderabad, India**

Building and maintaining high-volume data processing and publishing services for a global financial platform serving 100+ countries.

**Key Responsibilities:**
- Deliver production-grade Java/Spring Boot APIs and SQL workflows
- Own end-to-end feature delivery: requirements → implementation → release
- Author unit and integration tests with GitHub Copilot acceleration
- Diagnose and resolve critical production incidents under tight SLAs
- Manage changes through GitHub Actions CI/CD and Change Request workflows

**Tech:** Java 8+ | Spring Boot | REST APIs | Liquibase | SQL Server | Oracle SQL | GitHub Actions

---

### Tata Consultancy Services (TCS) — Associate Consultant to IT Analyst
**Apr 2016 – Aug 2022**

#### Clinics Without Walls (CWOW) — DaVita Inc. | Healthcare
*Nov 2018 – Aug 2022*

Delivered features for a kidney dialysis management platform supporting US outpatient centers.

- Owned end-to-end delivery for Labs Management and PMT modules
- Delivered using Java 8, Spring Boot, Angular 7, TypeScript, Bootstrap
- Authored low-level and high-level design documents
- Mentored new team members on Angular architecture

#### Product Maintenance — McKesson Corporation | Pharmaceutical
*Apr 2016 – Nov 2018*

Developed the Product Maintenance module for pharmaceutical item master data.

- Built responsive UI using AngularJS, JavaScript, jQuery, HTML5, CSS3
- Collaborated with business stakeholders to validate requirements

---

### Kantar GDC — Web Developer
**Nov 2012 – Apr 2016 | Hyderabad, India**

- Developed web applications for market research platforms
- Built reusable UI components and contributed to UI standardization

---

## 🎓 Education

| Degree | Institution | Timeline | Score |
|--------|-------------|----------|-------|
| **PGP AI & Machine Learning** | Great Learning | Aug 2025 – Sep 2026 | 4.25/5.0 |
| **Master of Computer Applications** | University College for Women, Koti (Osmania University) | 2012 | 89.9% |
| **B.Sc. (MECs)** | SSB Degree College (Sri Venkateswara University) | 2009 | 80.5% |

**PGP Curriculum:** Machine Learning | Deep Learning | Computer Vision | NLP with GenAI | Advanced Generative AI | Advanced ML & MLOps | RAG and LLM Applications

---

## 🏆 Certifications & Awards

**Certifications**
- AWS Certified Solutions Architect — Amazon Web Services (Dec 2025)
- VSkills Certified Angular 7 Developer — VSkills (Aug 2024)

**Recognition**
- Outstanding Performer of the Year — 2019
- Teammate of the Quarter — 2021
- Best Team Award — for measurable application performance improvement
- Applause Award — for client logistics excellence beyond project scope

---

## 📊 GitHub Stats

[![Madhavi's GitHub Stats](https://github-readme-stats.vercel.app/api?username=MadhaviS2504&theme=nord&show_icons=true&hide_border=true&count_private=true)](https://github.com/MadhaviS2504)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=MadhaviS2504&theme=nord&layout=compact&hide_border=true)](https://github.com/MadhaviS2504)

---

## 🌐 LinkedIn & GitHub Integration

### LinkedIn Profile
[Visit my LinkedIn](https://www.linkedin.com/in/madhavi-surapuraju) for:
- Professional experience timeline
- Endorsements and recommendations
- Industry network connections

### GitHub Portfolio
[View my GitHub](https://github.com/MadhaviS2504) for:
- Complete project code and implementations
- ML notebooks and tutorials
- Open-source contributions

### How to Use Both Profiles Together
1. **LinkedIn:** First impression, professional narrative, network presence
2. **GitHub:** Technical proof of work, project depth, coding practices
3. **This README:** Bridge between both—executive summary + detailed technical showcase

---

## 📍 Quick Reference Card

```
┌─────────────────────────────────────────────────────────────┐
│ NAME: Madhavi Surapuraju                                     │
│ TITLE: AI/ML Engineer | GenAI | Full Stack                  │
│ EXP: 13+ Years (Banking & Healthcare)                       │
│ FOCUS: RAG, LLMs, Agentic AI, Computer Vision, MLOps        │
├─────────────────────────────────────────────────────────────┤
│ CURRENT: Senior Engineer, JPMorganChase                      │
│ EDUCATION: PGP AI & ML (4.25/5.0) | MCA | AWS Certified     │
│ LOCATION: Hyderabad, India                                  │
│ NOTICE: 60 Days                                             │
│ STATUS: Open to Remote & Relocation                         │
├─────────────────────────────────────────────────────────────┤
│ REACH OUT:                                                  │
│ LinkedIn:  linkedin.com/in/madhavi-surapuraju               │
│ GitHub:    github.com/MadhaviS2504                          │
│ Email:     madhavis.2504@gmail.com                          │
│ Phone:     +91-9959578125                                   │
└─────────────────────────────────────────────────────────────┘
```

---

<div align="center">

### "Building AI solutions that matter — from research to production."

**Share, star, or connect with me on LinkedIn or GitHub!**

</div>

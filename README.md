👋 Hi, I'm Sanjana Garimella

I build machine learning systems that run in production — from large-scale data pipelines and parameter-efficient fine-tuning to LLM applications and the infrastructure that connects them.

My focus is on what happens after the model exists: how data choices shape performance, how retrieval and pipeline design change outputs, and how systems stay stable under real-world constraints like latency, failures, and distributional shift.

Previously a Software Developer at IBM building enterprise-scale security automation for z Systems. Now an MS Data Science student at UC San Diego, studying ML Systems, Scalable Data Platforms, and Data-Centric AI.

📬 sanjanagarimella6@gmail.com · [LinkedIn](https://www.linkedin.com/in/sanjana--garimella/)

---

## 🔬 Research & Technical Interests

I'm interested in building ML systems that are interpretable, reliable, and designed to work under real-world constraints not just optimized for benchmark performance.

My current focus is on data-centric approaches to model improvement, evaluation-driven development, and the systems-level challenges of deploying LLM applications in clinical AI and large-scale data infrastructure.

---

# 💼 Experience

**Research Assistant — University of California, San Diego**
- Support large-scale neuroscience research by managing Python-based data workflows and MongoDB databases.
- Improve workflow automation, reliability, and computational reproducibility across collaborative research environments.

**Software Developer — IBM**
- Fine-tuned and deployed a LLaMA-based model on IBM Cloud to automate multi-cloud infrastructure provisioning decisions, achieving a 40% reduction in manual intervention across enterprise deployment workflows.
- Contributed to an IBM Research semiconductor data analysis project, applying statistical analysis and data engineering techniques to derive insights from complex hardware performance datasets.
- Built security scanning pipelines in Python integrating five vulnerability scanning tools across production projects, enforcing compliance across 18 subsystems via REST APIs at release time.
- Onboarded 100+ repositories into the SPbD compliance framework by building Python-based integration scripts that standardized security configurations and enforced consistent coverage across global development teams.
- Developed Python scripts using REST APIs to detect and resolve inconsistencies across multiple open-source vulnerability scanning tools including GitHub, Mend, Twistlock, and OWASP Dependency Check — identifying mismatches in dependency tracking, scan coverage, and library versioning across production repositories.
- Designed and deployed a Grafana dashboard on a virtual machine backed by InfluxDB, ingesting and visualizing time-series security scan results across multiple vulnerability scanning tools to provide upper management with actionable visibility into vulnerability trends and mitigation priorities.
- Implemented LDAP authentication and certificate-based access control to secure dashboard access, restricting visibility to authorized stakeholders across distributed teams.

  
**Software Developer Intern — IBM**
- Designed and deployed a Grafana dashboard on a virtual machine backed by InfluxDB, ingesting 
  and visualizing time-series security scan results across multiple vulnerability scanning tools 
  to provide upper management with actionable visibility into vulnerability trends and mitigation 
  priorities.
- Implemented LDAP authentication and certificate-based access control to secure dashboard access, 
  restricting visibility to authorized stakeholders across distributed teams.

### Machine Learning Intern — Indian Servers
Fine-tuned a COCO-pretrained Mask R-CNN (ResNet-50 + FPN) on 59 images using transfer learning, 
CUDA memory management, and multi-scale augmentation achieving BBox AP 15.1 (AP50 = 27.6) 
and Segm AP 12.2, a result that typically requires 10x more data.

---

# 🎓 Education

**Master's in Data Science**  
University of California, San Diego  
2025 - 2027

**B.Tech Computer Science**  
KL University  
2019 - 2023

---

## 🔧 Key Projects

---

## 🚕 Cloud-Native Big Data Pipeline & Distributed Analytics Engine

🔗 [Repository](https://github.com/blue-octopus235/dsc291-2026)

Built a distributed data processing pipeline for 3.4B NYC taxi trips (57GB) stored on S3.

**Highlights**
- Distributed ETL pipeline using Dask and PyArrow processing 443 parquet files directly from S3
- Reduced 3.41B rows to 2.9M aggregated rows achieving 660x compression
- Implemented parallel month-wise processing with automated reporting
- Performed distributed PCA and geospatial demand analysis

**Tech Stack**
Python • Dask • PyArrow • AWS S3 • Parquet • Multiprocessing • Folium

---

## 🏥 MediDB — Multi-Model Clinical Decision Support System

🔗 [Repository](https://github.com/eemilycchen/drug_safety_and_recommendation)

A clinical decision support system combining relational, graph, and vector databases to generate 
patient-specific drug safety recommendations.

**Highlights**
- PostgreSQL for structured patient medication records
- Neo4j for drug interaction graphs capturing complex multi-drug relationships
- Qdrant for vector similarity search on adverse reaction profiles
- End-to-end ETL pipeline connecting three database paradigms into unified patient safety recommendations

**Tech Stack**
Python • PostgreSQL • Neo4j • Qdrant • SQL • Vector Search • ETL

---

## 🤖 Socially-Aware Spatial Markov Random Field Recommendation System

🔗 [Repository](https://github.com/sanjana-garimella/socially-aware-spatial-markov-random-field-for-personalized-recommendation)

Designed a top-N recommendation system tackling cold-start users and extreme sparsity (99.99%) 
in the Epinions dataset — deployed as a production-ready FastAPI service with real-time inference.

**Highlights**
- Combined Bayesian Logistic Regression with a Spatial Markov Random Field for probabilistic recommendation
- Engineered 35+ social and behavioral features integrating user behavior, content signals, and trust networks
- Achieved 25% improvement in AUC over baseline methods
- Deployed three model variants (Jaccard, Bayesian, Social MRF) with A/B testing dashboard and versioned artifacts via Dockerized FastAPI on Hugging Face

**Tech Stack**
Python • NumPy • Pandas • Scikit-learn • FastAPI • Docker • InfluxDB • Bayesian Modeling • Social Network Analysis

---

## 🧬 MediRare — Multimodal AI for Rare Disease Misdiagnosis Detection

🔗 [Repository](https://github.com/sanjana-garimella/MediRare)

A multimodal AI research system that mines medical literature figures using computer vision, 
extracts misdiagnosis patterns from PubMed case reports using NLP, and connects signals across 
diseases using an LLM reasoning agent — targeting the 6+ year average diagnosis delay for rare 
autoimmune diseases.

**Highlights**
- CV pipeline fine-tuning ResNet/ViT on medical figures extracted from open-access PubMed PDFs, 
  classifying rash images, lab charts, histology slides, and pathway diagrams
- NLP pipeline using BioBERT/PubMedBERT to mine thousands of case reports and construct a 
  structured disease misdiagnosis knowledge graph (NetworkX)
- MCP reasoning agent deployed via vLLM that queries the misdiagnosis graph, retrieves semantically 
  similar cases via FAISS/ChromaDB, and synthesizes per-disease research reports with misdiagnosis 
  pathways and research gaps
- Integrates PubMed, Orphanet, OMIM, and HPO data sources covering 6,500+ rare diseases

**Tech Stack**
PyTorch • HuggingFace • BioBERT • spaCy • vLLM • LangChain • MCP • FAISS • ChromaDB • NetworkX • Streamlit

---

## 🌐 Other Projects

### ✈️ Take a Trip — Travel & Hospitality Platform
🔗 [Repository](https://github.com/sdp-projects/travel_tourism_hospitaity)

Developed a trip planning platform across 10+ cities in India, improving query efficiency and 
reducing page load time by 30%.

**Tech Stack**
Python • Django • MySQL • HTML • CSS • JavaScript

---

### 🌱 Green Grow — Green Entrepreneurship Platform
🔗 [Repository](https://github.com/sanjana-garimella/green-grow)

Platform connecting entrepreneurs, experts, investors, and customers to promote sustainable products, 
deployed on AWS EC2 and RDS.

**Tech Stack**
Spring Boot • MySQL • AWS • Java • JSP

---

# 🧰 Technical Skills

**Languages**
Python • SQL • Java • R

**Machine Learning & DL**
PyTorch • HuggingFace • Scikit-learn • TensorFlow • BioBERT • ResNet • ViT • Mask R-CNN • LoRA/QLoRA • vLLM

**LLM & Agents**
LangChain • MCP • RAG • FAISS • ChromaDB • spaCy

**Data Engineering**
Dask • PyArrow • Parquet • NumPy • Pandas

**Databases**
PostgreSQL • Neo4j • Qdrant • MongoDB • InfluxDB • MySQL

**Infrastructure & Tools**
Docker • AWS (S3, EC2) • IBM Cloud • Hugging Face • Jenkins • Grafana • Streamlit • GitHub

**Frameworks**
FastAPI • Flask • Django • Spring Boot

---

## 🏅 Achievements

🏆 **Star of the Month — IBM**
Enhanced MEND open-source vulnerability tracking and automated onboarding workflows across 
global development teams.

🌟 **Infrastructure All-Hands Recognition — IBM**
Streamlined Security and Privacy by Design (SPbD) onboarding across 18 subsystems serving 
worldwide teams.

🎖 **People's Choice Award — IBM Developer Jumpstart**
Built a LLaMA-based provisioning automation system that reduced cloud infrastructure costs by 
40% through LLM-driven deployment decisions across multi-cloud environments.

---

## 📚 Writing

📊 [Role of Data Science in Healthcare](https://www.linkedin.com/pulse/video-blog-role-data-science-health-care-g-g-sanjana)
How data science is transforming healthcare analytics and patient outcomes.

🤖 [Tackling Cold-Start Recommendations with Socially-Aware Spatial Markov Models](https://www.linkedin.com/pulse/tackling-cold-start-recommendations-socially-aware-markov-garimella-9sufc)
Deep dive into solving cold-start and sparsity problems using probabilistic modeling and social trust signals.

🌍 [Take a Trip — System Design for Travel Platforms](https://www.linkedin.com/pulse/field-study-travel-tourism-hospitality-sector-gayatri-sanjana)
System design and query optimization for a multi-city travel planning platform.

🌱 [Green Grow — Building Technology for Sustainable Entrepreneurship](https://www.linkedin.com/pulse/green-grow-garimella-gayatri-sanjana)
Building technology ecosystems that connect entrepreneurs, investors, and sustainable product markets.

---

## 📬 Contact

📧 sanjanagarimella6@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/sanjana--garimella/)

---

*Open to collaborating on machine learning systems, data infrastructure, and applied AI research.*

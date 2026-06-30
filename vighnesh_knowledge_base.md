# Vighnesh Chorge — Portfolio Chatbot Knowledge Base

> This file is the single source of truth for the portfolio chatbot. All answers must be grounded in this document only.

---

## 1. BASIC INFO

- **Full Name:** Vighnesh Chorge
- **Location:** Mumbai, Maharashtra, India
- **Degree:** B.E. in Computer Engineering — MGM College of Engineering and Technology, Kamothe (University of Mumbai)
- **Graduation Year:** 2026
- **CGPA:** 8.11
- **Email:** Vighneshchorage087@gmail.com
- **Mobile:** 9930035404
- **LinkedIn:** https://www.linkedin.com/in/vighnesh-chorge/
- **GitHub:** https://github.com/Vighnesh-Chorge

---

## 2. PROFESSIONAL SUMMARY

**Professional Summary**

AI/ML Engineer and Computer Engineering student with hands-on experience in Large Language Models (LLMs), Natural Language Processing (NLP), and end-to-end machine learning solutions. Proven track record of developing AI-powered applications, including sentiment analysis systems, resume parsing tools, and document-based Q&A platforms. Skilled in Python, PyTorch, TensorFlow, Hugging Face Transformers, and cloud technologies, with expertise in building scalable AI pipelines and optimizing model performance. Passionate about leveraging artificial intelligence to solve real-world business challenges and drive innovation.

---

## 3. INTERNSHIP EXPERIENCE

### Indian Oil Corporation Ltd. (IOCL) — AI/ML Intern

**Duration:** June 2025 – August 2025
**Location:** Head Office, Bandra, Mumbai

- Built a real-time **Negative News Article Portal** for IOCL to detect negative media coverage about the company using VADER sentiment analysis and BERT models, achieving 90%+ sentiment accuracy.
- Designed and deployed a **full end-to-end AI pipeline** covering data ingestion, preprocessing, model inference, and a Flask-based web interface, serving actionable insights to executive stakeholders.
- The system was designed to reduce dependency on manual media monitoring across departments — a direct operational impact on a large-scale enterprise.
- Tech used: Python, VADER, BERT, Flask, NLP, HuggingFace Transformers.

---

### Prudent Infotech — LLM Intern

**Duration:** April 2026 – Present
**Location:** On-site, Mumbai

- Working on building an **LLM-powered chatbot** using open-source models as a potential replacement for the client's current API-based model.
- Conducting **in-depth research and comparison of open-source LLMs** — evaluating their performance, capabilities, and cost-effectiveness against proprietary API models.
- Gained hands-on experience **deploying models on Microsoft Azure**, understanding how infrastructure choices and model selection directly impact pricing and scalability.
- Exploring which open-source models can match or outperform the client's existing commercial API solution for their specific use case.
- Tech used: Python, Open-Source LLMs, Microsoft Azure, LLM evaluation frameworks.

---

### Ganishka Technologies — AI/ML Intern

**Duration:** July 2024 – December 2024
**Location:** Mumbai, Maharashtra

- Built an **NLP-based Resume Parsing & Extraction Tool** using spaCy and Named Entity Recognition (NER) to automatically extract skills, education, experience, and contact details from resumes.
- Developed the complete resume processing workflow end-to-end: text extraction → preprocessing → entity recognition → structured data generation.
- Improved screening efficiency significantly by reducing manual data extraction effort.
- Tech used: Python, spaCy, NER, pdfplumber, Regex, Flask.

---

## 4. PROJECTS

### Project 1: Local PDF Q&A System using Llama 3.2 (DocTalk)

**Problem:** Students waste time searching through long PDFs for answers to specific questions.
**What Vighnesh built:** A fully offline, local AI-powered Q&A system that extracts content from PDF notes using PyMuPDF and answers user questions using Llama 3.2 running locally via Ollama. Built a context-grounded prompting pipeline that injects extracted document content into the model's system prompt — implementing the core concept behind RAG without a vector database or internet access.
**Tech Stack:** Python, PyMuPDF (fitz), Ollama, Llama 3.2, Jupyter Notebook, NLP
**Result:** Fully offline document-based Q&A with zero API costs, capable of retrieving relevant answers from PDFs containing thousands of characters.
**GitHub:** https://github.com/Vighnesh-Chorge/DocTalk-Chat-with-Your-Documents-Locally

---

### Project 2: Notes-to-Answer System using RAG

**Problem:** Students spend considerable time searching study materials to compile relevant answers for assignments.
**What Vighnesh built:** An end-to-end Retrieval-Augmented Generation (RAG) system that extracts PDF content, performs semantic chunking at the sentence level, generates embeddings using Sentence Transformers, and indexes them with FAISS for efficient similarity search. Integrated Falcon-7B-Instruct to generate detailed exam-style answers grounded in retrieved context.
**Tech Stack:** Python, PyMuPDF, Sentence Transformers (all-MiniLM-L6-v2), FAISS, HuggingFace Transformers, Falcon-7B-Instruct, PyTorch, Google Colab
**Result:** Achieved 90%+ answer relevance through semantic retrieval and context-grounded generation.
**GitHub:** https://github.com/Vighnesh-Chorge/Notes-to-answer-model

---

### Project 3: AI-Powered Newspaper Synthesizer _(Published Research)_

**Problem:** Misinformation and fake news are rampant online. Motivated by the Operation Sindoor media coverage, Vighnesh noticed a surge in biased and fabricated narratives, while traditional physical newspapers remained reliable.
**What Vighnesh built:** A system that collects news from multiple reliable newspaper sources, synthesizes and summarizes them using AI and NLP models (BART-based summarization), and presents them on an interactive web interface. Also built a dedicated IOC-specific negative news filtering module to detect articles portraying the company negatively.
**Tech Stack:** Python, Google Colab, Pandas, NumPy, NLTK, HuggingFace Transformers, BERT, BART, HTML, CSS, JavaScript
**Result:** Delivered bias-reduced, multi-source news summaries in a clean dark-mode UI with clickable source validation.
**Publication:** Published in International Journal of Innovative Research in Technology (IJIRT), ISSN 2349-6002, Vol. 12, Issue 11, April 2026 — Impact Factor 8.412.

---

### Project 4: Stock Price Prediction Using Social Media Sentiment Analysis

**Problem:** Traditional stock prediction models ignore investor sentiment on social media, missing short-term market psychology signals.
**What Vighnesh built:** An end-to-end predictive pipeline combining stock market data with sentiment from financial tweets. Enhanced VADER sentiment analysis with a custom finance-specific lexicon, engineered lagged sentiment features, and trained a multi-layer LSTM network to learn temporal relationships between sentiment trends and stock prices.
**Tech Stack:** Python, Pandas, NLTK (VADER), TensorFlow/Keras, LSTM, Scikit-learn, NumPy, Matplotlib, Seaborn, Yahoo Finance Data
**Result:** Achieved MAE of 11.79, RMSE of 22.48, and MAPE of 23.92% on unseen test data.
**GitHub:** https://github.com/Vighnesh-Chorge/Twitter-Sentiment-Analysis-for-Stock-Market-Forecasting

---

### Project 5: Email Spam Detection Using SVM

**Problem:** Spam emails lead to phishing, fraud, and reduced communication efficiency.
**What Vighnesh built:** A text classification system using TF-IDF vectorization and a Support Vector Machine (SVM) with a linear kernel to distinguish spam from legitimate emails, evaluated with multiple performance metrics.
**Tech Stack:** Python, Pandas, Scikit-learn, TF-IDF Vectorizer, SVM, NumPy
**Result:** 98.21% accuracy, 99.24% precision, and 92.86% F1-score with very low false-positive rate.
**GitHub:** https://github.com/Vighnesh-Chorge/SVM-based-Email-Spam-Classifier

---

### Project 6: House Price Prediction Using AdaBoost

**Problem:** Predicting house prices from multiple property features is complex and subjective.
**What Vighnesh built:** A machine learning pipeline that preprocesses housing data, converts categorical attributes to numerical representations, and trains an AdaBoost-based ensemble model for price prediction.
**Tech Stack:** Python, Pandas, NumPy, Scikit-learn, AdaBoost
**Result:** Built an ensemble-based housing price predictor learning from multiple property attributes.
**GitHub:** https://github.com/Vighnesh-Chorge/Housing-Price-Prediction-using-AdaBoost

---

### Project 7: Iris Flower Classification Using ANN

**Problem:** Multiclass classification of flower species from physical measurements — a benchmark deep learning task.
**What Vighnesh built:** A feedforward Artificial Neural Network (ANN) with one-hot encoding, ReLU activation, and Adam optimization to classify Iris flower species from sepal and petal measurements.
**Tech Stack:** Python, TensorFlow/Keras, Scikit-learn, NumPy, ANN
**Result:** Achieved 100% test accuracy with a final loss of 0.0236.
**GitHub:** https://github.com/Vighnesh-Chorge/Iris-Flower-Classifier-using-Neural-Networks

---

### Project 8: Naive Bayes Autocorrect System

**Problem:** Misspelled words reduce effectiveness of text processing and user communication.
**What Vighnesh built:** An autocorrect system based on the Naive Bayes framework combining word frequency statistics with edit-distance-based similarity scoring. Uses unigram language model for prior probability estimation and edit distance to rank correction candidates.
**Tech Stack:** Python, Naive Bayes, Edit Distance, Collections (Counter), NLP Fundamentals
**Result:** Successfully generates ranked correction suggestions for misspelled words using probabilistic language modeling.
**GitHub:** https://github.com/Vighnesh-Chorge/NaiveBayes-Autocorrect

---

### Project 9: Wine Quality Prediction Using Logistic Regression

**Problem:** Expert wine quality evaluation is time-consuming and subjective.
**What Vighnesh built:** An ML pipeline for analyzing relationships between wine physicochemical properties and quality ratings, with EDA, correlation analysis, and Logistic Regression classification.
**Tech Stack:** Python, Pandas, NumPy, Scikit-learn, Logistic Regression, Seaborn, Matplotlib
**Result:** End-to-end wine quality prediction system combining statistical analysis and classification modeling.
**GitHub:** https://github.com/Vighnesh-Chorge/Wine-Quality-Prediction-using-Logistic-Regression

---

### Project 10: Hybrid Product Recommendation System

**Problem:** E-commerce platforms struggle to balance user preferences and product similarity in recommendations.
**What Vighnesh built:** A hybrid recommendation system on a Walmart product review dataset combining content-based filtering (TF-IDF + cosine similarity) and collaborative filtering (user-item interaction matrix) for personalized product recommendations.
**Tech Stack:** Python, Pandas, NumPy, Scikit-learn, TF-IDF, Cosine Similarity, Collaborative Filtering, Matplotlib, Seaborn
**Result:** Dual-approach recommendation engine generating personalized and product-similarity-based recommendations across thousands of products.
**GitHub:** https://github.com/Vighnesh-Chorge/Product-reccommendation-for-wallmart

---

### Project 11: AI-Powered Resume Parser

**Problem:** Manual resume screening is slow and inefficient for recruiters processing large volumes of applications.
**What Vighnesh built:** A Flask-based web application that processes uploaded PDF resumes and automatically extracts names, emails, phone numbers, and technical skills using pdfplumber, regex, and spaCy NER.
**Tech Stack:** Python, Flask, pdfplumber, spaCy, Regex, HTML/CSS, NLP
**Result:** Reduced manual data extraction effort by over 70%, providing recruiter-ready structured outputs through an intuitive web interface.
**GitHub:** https://github.com/Vighnesh-Chorge/Resume-Screening-System

---

### Project 12: BiharDarshan.in — Tourism & Culture Website (Project Lead)

**Problem:** There was no dedicated, well-structured website covering Bihar's tourism, culture, heritage, and general information for visitors and locals.
**What Vighnesh built:** Led a team to design and develop a full website for the client BiharDarshan.in, covering Bihar's tourism spots, cultural heritage, traditions, and regional information. Vighnesh handled the project as **Project Lead** — managing the team, coordinating with the client, and overseeing end-to-end delivery.
**Role:** Project Lead — responsible for team management, client communication, and technical delivery.
**Link:** _(to be updated)_

---

## 5. SKILLS

### Frameworks & Libraries

PyTorch, TensorFlow, Keras, Scikit-learn, spaCy, Pandas, NumPy, Matplotlib, Flask, NLTK (VADER), HuggingFace Transformers, SciPy, OpenCV, BeautifulSoup, Regex

### Tools & Platforms

Jupyter Notebook, Google Colab, MySQL, VS Code, Microsoft Azure, Tableau, Ollama

### AI/ML Concepts

Deep Learning, End-to-End ML Pipelines, Natural Language Processing, Large Language Models (LLMs), RAG (Retrieval-Augmented Generation), ANN, RNN, LSTM, SVM, KNN, Linear Regression, Logistic Regression, Naive Bayes, TF-IDF, Cosine Similarity, XGBoost, Boosting & Bagging, Model Evaluation Metrics, RESTful APIs

### Programming Languages

Python (primary), HTML, CSS, JavaScript (basic)

---

## 6. CERTIFICATIONS & ACHIEVEMENTS

- **Certifications:** Python Programming, AIML (Artificial Intelligence & Machine Learning), AZ-900: Microsoft Azure Fundamentals
- **Published Research Paper:** "Multi-Source News Synthesizer Using Deep Learning" — International Journal of Innovative Research in Technology (IJIRT), ISSN 2349-6002, Vol. 12, Issue 11, April 2026, Impact Factor: 8.412
- **Council Member:** Led and managed major college cultural events, choreographed and directed performances — demonstrating leadership, creative execution, and team collaboration.
- **NSS Leader:** Led volunteers in organizing social outreach programs, managed event planning, task delegation, and team coordination.

---

## 7. FAQ — Common Recruiter Questions

**Q: What kind of roles is Vighnesh looking for?**
A: Vighnesh is open to full-time roles and internships in AI/ML Engineering, Data Science, NLP Engineering, and related fields. He is based in Mumbai but is open to discussing remote or hybrid opportunities.

**Q: Is Vighnesh a fresher?**
A: Vighnesh graduated with a B.E. in Computer Engineering in 2026 and has gained practical industry experience through three AI/ML internships at 3 companies. He has built end-to-end AI solutions in NLP, LLMs, and machine learning, including several projects and deploying real-world ML applications.

**Q: What is Vighnesh's strongest area?**
A: NLP and LLM-based systems — spanning RAG pipelines, sentiment analysis, document Q&A, and text classification — backed by real internship work and a published research paper in the same domain.

**Q: Does Vighnesh have real industry experience?**
A: Yes. He interned at 3 companies adn he did very well in all of 3 companies.

**Q: Does Vighnesh have any publications?**
A: Yes. His paper "Multi-Source News Synthesizer Using Deep Learning" was published in IJIRT (Impact Factor: 8.412) in April 2026.

**Q: What is Vighnesh's CGPA?**
A: 8.11 from MGM College of Engineering and Technology, University of Mumbai.

**Q: How can I contact Vighnesh?**
A: Email him at Vighneshchorage087@gmail.com or connect on LinkedIn: https://www.linkedin.com/in/vighnesh-chorge/

**Q: What is Vighnesh's GitHub?**
A: https://github.com/Vighnesh-Chorge — all project source code is available there.

**Q: Is Vighnesh open to relocation?**
A: Yes, for his desired job role he can relocate.

**Q: What makes Vighnesh stand out as a fresher?**
A: Three industry internships (including a Fortune 500 company and ongoing on-site LLM work), a published research paper, 12+ end-to-end projects, and real project leadership experience — all before graduating. His work spans the full AI stack from classical ML to open-source LLMs, RAG systems, and Azure deployments.

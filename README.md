# Healthcare Topic Modeling using LDA, KeyBERT, and TF-IDF

A portfolio-ready NLP project that applied topic modeling and keyword extraction to analyze how Industry 4.0 technologies shaped healthcare research.

This project combined one broad literature-level analysis across Healthcare 4.0 and four focused subdomain studies in cardiology, oncology, orthopedics, and health records. The goal was to transform large collections of research papers into interpretable themes using Latent Dirichlet Allocation (LDA), KeyBERT, and TF-IDF.

## Project Overview

This repository includes five notebooks:

    LDA_thematic_.ipynb     # Broad thematic analysis of Industry 4.0 in healthcare
    Cardiology.ipynb        # Topic modeling of cardiology-focused literature
    Oncology.ipynb          # Topic modeling of oncology-focused literature
    Orthopedics.ipynb       # Topic modeling of orthopedic literature
    healthRecords.ipynb     # Topic modeling of health records and digital data-management literature

Together, these notebooks form a structured NLP workflow for analyzing healthcare literature at both the macro level and the subdomain level.

## Problem Statement

The rapid growth of Industry 4.0 technologies such as IoT, artificial intelligence, blockchain, robotics, cloud systems, and wearable devices has significantly influenced healthcare research and innovation.

However, the increasing volume of academic literature makes it difficult to manually identify dominant themes, compare topic patterns across medical domains, and understand how technology adoption varies across healthcare applications.

This project addressed that challenge by using topic modeling and keyword extraction techniques to systematically analyze healthcare literature and surface the most meaningful research themes.

## Objectives

The main objectives of this project were to:

- Identify dominant themes across Industry 4.0 healthcare literature
- Compare research patterns across key healthcare subdomains
- Evaluate how technologies such as AI, IoT, robotics, and blockchain appear in different areas of medicine
- Build an interpretable NLP workflow for exploratory literature review and thematic analysis
- Translate unstructured research text into structured, recruiter-friendly insights

## Dataset

### Industry 4.0 in Healthcare Dataset

The broad thematic analysis was built on a corpus of 100 research papers focused on Industry 4.0 in healthcare.

### Healthcare Subdomain Dataset

The subdomain-level analysis used 80 research papers, divided evenly across four healthcare areas:

- 20 papers in cardiology
- 20 papers in oncology
- 20 papers in orthopedics
- 20 papers in health records / pathology-related digital systems

The literature was collected from academic research sources and curated to focus on healthcare applications of Industry 4.0 technologies.

## Methodology

Across the notebooks, I implemented a text analytics pipeline consisting of the following stages:

1. Text extraction
2. Lowercasing and normalization
3. Removal of punctuation and digits
4. Stopword removal
5. Lemmatization
6. TF-IDF vectorization
7. KeyBERT keyword extraction
8. LDA topic modeling
9. Topic interpretation and comparison

This approach allowed the project to move from raw research text to interpretable topic clusters and keyword-based thematic summaries.

## Model Configuration

### KeyBERT

- Extracted 70 key phrases per document
- Used an n-gram range of 1 to 3
- Helped generate interpretable keyword summaries for research documents

### LDA

- Industry 4.0 notebook: 5 topics, 200 iterations
- Healthcare subdomain notebooks: 4 topics, 200 iterations
- Used to discover latent topic clusters across each literature corpus

These configurations were selected to balance interpretability and thematic separation across the research-paper collections.

## Key Findings

### 1. Industry 4.0 in Healthcare: Major Themes

The broad thematic analysis identified five major themes across Healthcare 4.0 research:

- Medical analytics and big data
- IoT, smart systems, and cloud computing
- Blockchain, privacy, and secure data exchange
- Robotics, sensors, and wearable monitoring
- Artificial intelligence and intelligent healthcare systems

These results showed that healthcare research was increasingly centered on connected monitoring systems, intelligent diagnostic support, secure digital data infrastructure, and automation-enabled treatment and decision-making.

### 2. Cardiology

The cardiology notebook highlighted strong themes around:

- IoT-enabled cardiovascular care
- ECG monitoring
- Telemedicine
- Wearables and remote patient monitoring
- Real-time cardiac data collection

This subdomain reflected how connected devices and monitoring technologies were reshaping cardiovascular care and personalized health management.

### 3. Oncology

The oncology notebook revealed themes around:

- AI and machine learning in cancer care
- Medical imaging
- Early detection and diagnosis
- Patient-centered treatment support
- Digital innovation in oncology workflows

The analysis showed that oncology literature strongly emphasized AI-assisted diagnostics, imaging-based decision support, and data-driven treatment approaches.

### 4. Orthopedics

The orthopedics notebook emphasized:

- Robot-assisted surgery
- Precision treatment systems
- Biomechanical modeling
- Rehabilitation technologies
- Computer-assisted orthopedic workflows

This analysis reflected the growing role of robotics and automation in surgical planning, orthopedic interventions, and rehabilitation support.

### 5. Health Records

The health records notebook focused on:

- Blockchain in healthcare
- Medical data security
- Privacy and trust
- Traceability
- Digital modernization of record systems

This subdomain showed that healthcare data infrastructure research was heavily centered on secure information exchange, privacy protection, and scalable digital health systems.

## Tools and Libraries

**Language:** Python  
**Environment:** Jupyter Notebook  
**Core Libraries:** pandas, NumPy, scikit-learn  
**NLP Libraries:** NLTK, spaCy, KeyBERT  
**Visualization:** Matplotlib, WordCloud  
**Methods:** LDA, TF-IDF, keyword extraction, topic modeling, text preprocessing

## Repository Structure

    Healthcare_Topic_Modelling/
    ├── LDA_thematic_.ipynb
    ├── Cardiology.ipynb
    ├── Oncology.ipynb
    ├── Orthopedics.ipynb
    ├── healthRecords.ipynb
    └── README.md

## How to Run

Clone the repository:

    git clone <your-repo-link>
    cd <your-repo-folder>

Create and activate a virtual environment:

    python -m venv venv
    source venv/bin/activate

For Windows PowerShell:

    python -m venv venv
    .\venv\Scripts\Activate.ps1

Install dependencies:

    pip install -r requirements.txt

Launch Jupyter Notebook:

    jupyter notebook

Open any notebook and run the cells in order.

If a `requirements.txt` file is not available yet, install the main dependencies manually:

    pip install pandas numpy scikit-learn nltk spacy matplotlib wordcloud keybert jupyter

## What I Focused On

- Building an end-to-end NLP workflow for literature-based thematic analysis
- Applying LDA, TF-IDF, and KeyBERT to unstructured healthcare research text
- Comparing macro-level Healthcare 4.0 themes with subdomain-specific topic patterns
- Translating topic modeling outputs into interpretable healthcare insights
- Using text analytics to support academic research analysis and trend discovery

## Recruiter-Friendly Highlights

- Analyzed 180 healthcare research papers across broad Healthcare 4.0 and four medical subdomains
- Built a complete NLP workflow using preprocessing, TF-IDF, KeyBERT, and LDA topic modeling
- Compared technology adoption patterns across cardiology, oncology, orthopedics, and health records
- Converted unstructured academic literature into structured themes and domain-level insights
- Demonstrated applied NLP, healthcare analytics, and research interpretation skills

## Future Improvements

Planned enhancements for this project include:

- Add a shared preprocessing pipeline across notebooks
- Create a `requirements.txt` file for reproducibility
- Export topic results to CSV or JSON
- Add coherence-score comparison visualizations
- Build a cross-domain topic comparison dashboard
- Improve notebook markdown documentation and storytelling
- Add topic-distribution charts directly to the README

## Author

Vaishnavi Kashyap  
MS in Computer Science, UMass Amherst

Interested in applied machine learning, natural language processing, healthcare analytics, and data-driven product development.

## Final Summary

This repository presents a combined view of healthcare-focused topic modeling projects that explored how Industry 4.0 technologies influenced modern healthcare research.

By using LDA, KeyBERT, and TF-IDF, the project identified both broad Healthcare 4.0 themes and domain-specific patterns across cardiology, oncology, orthopedics, and health records. The project demonstrates how NLP can turn large volumes of healthcare literature into interpretable insights for research, analytics, and technology trend discovery.

---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.


# Analyzed the clinical applicability of digital retinal biomarkers in the detection of systemic disorders (such as Bipolar and Alzheimer’s) 
# Developed an explainable ML pipeline for the diagnosis of Diabetic Retinopathy (DR) and Hypertensive Retinopathy (HTR) using digital biomarkers extracted from the retinal vasculature. Python, OpenCV       
# Achieved ROC-AUC ∼ 0.70 for DR detection and stage-grading; 0.98 for HTR detection; 0.89 for HTR stage-grading
# Assessed the applicability of clinical AI in retinal imaging-based teleophthalmology services in India

# Developed a clinician-in-the-loop AI pipeline for the extraction and quantification of retinal vascular parameters with results within ±8% of the research benchmark tool SIVA. Python, OpenCV, Django
# Organized weekly brainstorming sessions for ideation, need analysis, and literature review on Dry Eye Disorder screening and anterior segment imaging
# Analyzed confounding factors in the grading criteria used by Retinopathy of Prematurity specialists and formulated a decision support system plan to address these issues

# Developed a test-case similarity search tool for impact analysis in software testing, with an accuracy of ∼ 95-98 %, that landed the first prize in Capgemini iSprint 2019 (West Division)
# Utilized NLP for tabular data processing and fine-tuned pre-trained ELMo (Embeddings from Language Models) to extract query and test-case embedding for semantic mapping
# D>esigned an interactive UI visualization scheme for the retrieved results using Python, t-SNE, and matplotlib

experience:

  - title: Research Assistant (HiWi)
    company: Max Planck Institute for Informatics
    company_url: 'https://www.mpi-inf.mpg.de/departments/visual-computing-and-artificial-intelligence'
    company_logo: org-mpi-logo-de
    location: Saarbruecken, DE
    date_start: '2025-03-01'
    date_end: '2025-06-30'
    description: |2-
        
        * Initiated benchmarking of parameterized quantum circuits with CUDA-Q and PyTorch, enabling scalability analysis for QML workloads.
        * Led literature review on quantum-optimized multi-model fitting in noisy point clouds, assessing applicability for robust shape fitting and 3D reconstruction.

  - title: AI and Data Science (AIQX) Intern
    company: BMW Group
    company_url: 'https://www.bmwgroup.com/en.html'
    company_logo: org-bmw-group_logo
    location: Munich, DE
    date_start: '2024-09-01'
    date_end: '2025-02-28'
    description: |2-
        
        *  Built multimodal anomaly detection pipelines for automotive quality assurance, achieving 100% recall and over 95% precision on production data.
        * Developed a hybrid defect inspection pipeline combining foundational models, classical computer vision, and statistical
        methods, reducing manual audit time by 70%.
        * Designed and implemented a VLM-based OCR pipeline for compliance documentation with >85% extraction accuracy on complex backgrounds, automating previously manual audits.

  - title: Research Assistant (HiWi)
    company: Max Planck Institute for Informatics
    company_url: 'https://www.mpi-inf.mpg.de/departments/visual-computing-and-artificial-intelligence'
    company_logo: org-mpi-logo-de
    location: Saarbruecken, DE
    date_start: '2023-10-01'
    date_end: '2024-08-31'
    description: |2-
        
        *  Converted large-scale 3D vision datasets into binary representations via state-of-the-art autoencoder, reducing storage overhead by 35% while preserving fidelity.
        * Applied contrastive learning in PyTorch to enhance query retrieval, increasing matching accuracy by 52%.
        * Simulated quantum ML models for pattern retrieval, establishing feasibility of hybrid AI–quantum methods.

  - title: ML Developer (Freelance)
    company: 
    company_url: ''
    company_logo: org-freelance_retail
    location: Remote
    date_start: '2021-11-01'
    date_end: '2022-09-30'
    description: |2-

        Zero-shot Retail Object Recognition 
        
        * Developed an object recognition pipeline for inventory management using TensorFlow and OpenCV, achieving >80% accuracy.
        * Applied unsupervised learning for real-time object segmentation of retail shelf images, reaching >90% accuracy.
        * Computed object recognition on unlabeled datasets via embedding similarity using pre-trained models for enhancing detection efficiency.

  - title: Clinical AI Research Intern
    company: Forus Health Pvt. Ltd.
    company_url: 'https://www.forushealth.com/'
    company_logo: org-forus_logo
    location: Bengaluru, IN
    date_start: '2021-01-16'
    date_end: '2021-06-30'
    description: |2-

        AI-assisted Retinal Disease Prognosis
        
        * Implemented a TensorFlow-based classification model for disease severity grading, achieving AUC of 0.98.
        * Integrated SHAP for interpretability, quantifying parameter influence on model predictions.
        * Curated and clinically validated datasets for eye disease diagnosis, ensuring high-quality training data.
        
  - title: Teaching Assistant
    company: Pandit Deendayal Energy University
    company_url: 'https://pdeu.ac.in/'
    company_logo: org-pdpu_logo
    location: Gandhinagar, IN
    date_start: '2020-09-01'
    date_end: '2020-12-31'
    description: |2-
        
        * Course: AI for Everyone (20IC206T)
    
  - title: Clinical AI Research Intern
    company: Forus Health Pvt. Ltd.
    company_url: 'https://www.forushealth.com/'
    company_logo: org-forus_logo
    location: Bengaluru, IN
    date_start: '2020-01-13'
    date_end: '2020-07-31'
    description: |2-

        Clinical Biomarker Assessments for Retinal Diseases
    
        * Led a team of 5 interns to develop a clinician-controlled image processing pipeline for disease parameter analysis.
        * Achieved results within ±8% of research benchmark SIVA in 3 months using OpenCV and TensorFlow.
        * Conducted a review of AI-based retinal imaging telecare services in India to enhance clinical outreach.

  - title: Machine Learning Intern
    company: Capgemini Technology Services Ltd.
    company_url: 'https://www.capgemini.com/in-en/'
    company_logo: org-capgemini_logo
    location: Gandhinagar, IN
    date_start: '2019-06-01'
    date_end: '2019-07-31'
    description: |2-
    
        Context-Sensitive Semantic Search Tool
        
        * Developed a semantic search tool for impact analysis in software testing, achieving 95% accuracy.
        * Generated embeddings using a pre-trained language model for semantic mapping of test cases.
        * Built an interactive visualization tool for search results using Python, t-SNE, and matplotlib.

  # * Anomaly detection models for multimodal data
  # * Cost savings through early error identification and reducing future servicing expenses
  # * Reliable real-time image analysis using Vision-Language models for Component Traceability
  
  # * QUBO formulation of classical learning models 
  # * Quantum annealing-based optimization
  # * Applications for 3D Computer Vision tasks
  
  # * Object recognition pipeline with 80% accuracy for optimized inventory management
  # * Unsupervised learning for real-time object localization and segmentation from retail shelf images
  # * Embeddings from a pre-trained model to analyze and identify similar objects in the unlabeled dataset
  
  # * Curatation and clinical-verification of custom dataset for eye disease diagnosis
  # * Classification model using TensorFlow for disease severity grading with accuracy rate (AUC) 0.98
  # * SHAP-based explanation of biomarker influence on the model predictions
  
  # * Clinician-controlled image processing pipeline for disease parameter analysis
  # * Results within ±8% of the research benchmark SIVA in 3 months
  # * Review of clinical AI-based retinal imaging telecare services in India to improve care outreach
  
  # * Semantic search tool for impact analysis in software testing with 95% accuracy
  # * Embeddings using a pre-trained language model (ELMo) for semantic mapping of test cases
  # * Interactive UI visualization scheme for the retrieved results
        
  # - title: CEO
  #   company: GenCoin
  #   company_url: ''
  #   company_logo: org-gc
  #   location: California
  #   date_start: '2021-01-01'
  #   date_end: ''
  #   description: |2-
  #       Responsibilities include:
        
  #       * Analysing
  #       * Modelling
  #       * Deploying
        
  # - title: Professor of Semiconductor Physics
  #   company: University X
  #   company_url: ''
  #   company_logo: org-x
  #   location: California
  #   date_start: '2016-01-01'
  #   date_end: '2020-12-31'
  #   description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---

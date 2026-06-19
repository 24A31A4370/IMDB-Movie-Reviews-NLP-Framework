# 🎬 IMDb Movie Reviews: Multi-Task NLP Architecture & Latent Language Modeling

A comprehensive, 4-week end-to-end Natural Language Processing (NLP) framework and machine learning engineering pipeline built using 50,000 IMDb movie reviews. This project spans classical lexicon text mining, statistical Named Entity Recognition (NER) tracking, and unsupervised Latent Dirichlet Allocation (LDA) topic modeling.

## 📊 Core Portfolio Milestones & Results
* **Week 1 & 2 (Exploratory Analytics & Lexicon Baselines):** Engineered text-length feature extractions and benchmarked VADER sentiment analytics, establishing a baseline identification accuracy of **68.40%**.
* **Week 3 (Named Entity Recognition Architecture):** Integrated `spaCy` transition-based parsing pipelines to extract and map volumetric entity counts across matching context sentiments (**PERSON**, **ORG**, **GPE**).
* **Week 4 (Latent Language Topic Modeling):** Scaled an unsupervised LDA model to observe language shifts across narrative tiers. Discovered that as review lengths increase, plot-summary density drops significantly while deep **Emotional Response** prose scales up from **28.83% to 48.14%**.

## 📁 Repository Directory Structure
├── week1.docx                          # Milestone 1 Project Report
├── week2.docx                          # Milestone 2 Project Report
├── week3.docx                          # Milestone 3 Project Report
├── week4.docx                          # Final Capstone Synthesis Report
├── Untitled-1.ipynb                    # End-to-end Python NLP execution pipeline
├── linguistic_trend_evolution.png       # LDA Topic distribution stacked chart
├── ner_sentiment_distribution.png       # Named Entity sentiment breakdown
├── review_length_chart.png              # Week 1 exploratory analysis plot
├── sentiment_confusion_matrix.png       # Week 2 classification matrix
├── requirements.txt                     # Application dependency registry
└── .gitignore                           # Prevents tracking massive local CSV datasets
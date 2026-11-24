# Behavioral Segmentation of Masculinity Survey Respondents (K-Means Clustering)

An unsupervised machine learning project analyzing FiveThirtyEight's *Masculinity Survey* dataset to uncover distinct behavioral segments based on emotional openness, social support-seeking, and interpersonal habits.

## Project Overview
* **Objective:** Segment male survey respondents into behavioral archetypes using K-Means clustering and compare their attitudes toward masculinity and demographic backgrounds.
* **Dataset:** FiveThirtyEight Masculinity Survey (`1,189` raw responses; `1,023` complete responses after ordinal encoding and missing-value filtering across `q0007` behavioral items).
* **Tech Stack:** Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn.

## Repository Structure
```text
masculinity-survey-clustering/
├── assets/
│   └── cluster_analysis.png         # Cluster behavioral profile & 2D PCA projection
├── data/
│   ├── masculinity.csv              # Survey dataset (1,189 respondents, 98 columns)
│   └── masculinity-survey.pdf       # Original survey questionnaire reference
├── notebooks/
│   └── masculinity_clustering.ipynb
├── .gitignore
├── requirements.txt
└── README.md
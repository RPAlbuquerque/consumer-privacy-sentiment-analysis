##🧠 Consumer Sentiment & Digital Privacy
Code Repository for the Research Paper
"Consumer Sentiment on Privacy: Contrasting Marketing Literature with Social Media Discourse"

📌 Overview
This repository contains all scripts and assets used to support the analyses presented in the paper, which explores how consumers express emotions and psychological consequences related to digital privacy on social media—and how these expressions align (or diverge) from the themes covered in the marketing literature.

The project is structured in two stages:

Literature Review Analysis — identification of emotions and psychological impacts studied in academic research.

Social Media Analysis — large-scale classification of 22,758 tweets using sentiment/emotion models and thematic clustering techniques.

📂 Folder Structure
📁 /data/               → Input data files (tweets, keyword lists, filtered outputs)  
📁 /notebooks/          → Jupyter Notebooks with step-by-step analyses  
📁 /scripts/            → Python scripts for pre-processing, classification, and modeling  
📁 /outputs/            → Figures, tables, and logs generated during the pipeline  


🧪 Key Methods & Tools
- Sentiment Analysis: CardiffNLP RoBERTa (TweetEval benchmark)
- Emotion Scoring: Empath (lexicon-based emotional intensity across 8+ dimensions)
- Psychological Impact Detection: Rule-based keyword matching
- Topic Modeling: BERT Embeddings + KMeans Clustering
- Temporal Trends: Matplotlib & Seaborn visualizations
- Cross-Validation: Tabulated results and heatmaps to assess consistency

🔁 Reproducibility
All notebooks and scripts are modular and reproducible on machines with Python 3.10+.
Hardware used: 64 CPU cores, 4 GPUs, 990 GB RAM (Harvard FASRC environment).
Libraries: transformers, pandas, matplotlib, seaborn, scikit-learn, tqdm, EmpathClient, and more.

To replicate results:
# Install dependencies (example)
pip install -r requirements.txt

# Run full analysis
python scripts/full_pipeline.py

🖼️ Example Outputs
Figure 1 — Tweet Volume Over Time
Figure 2 & 3 — Temporal Evolution of Psychological and Well-being Impacts
Figure 4 — Heatmap: Psychological Impacts × Sentiment
Table 3 — Top 10 Thematic Clusters (from BERT + KMeans)


🤖 AI Contributions
Some parts of the pipeline were enhanced using:
ChatGPT: Python code suggestions and keyword validation
GitHub Copilot: Auto-completion of repetitive functions and syntax helpers
All content was manually reviewed and validated by the authors.



📬 Contact
For academic collaborations or questions, please reach out to the authors:
Rafael Albuquerque - Harvard Center for Geographic Analysis & Federal University of Rio Grande do Sul (UFRGS)
Carla F. Silveira Netto - Pontifical Catholic University of Paraná (PUCPR)

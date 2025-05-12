<h1 align="center">📰 Fake News Detection with GCN-Transformer</h1>

<p align="center">
  <em>A hybrid model for identifying misinformation through content and user network structure.</em><br>
  <strong>Based on my MSc Thesis in Data Analytics (2025)</strong>
</p>

---

## Why This Project would benefit?

Fake news isn't just about the text — it's about <strong>how it spreads</strong>.  
Traditional models focus only on content. This model captures both:
- Textual meaning (via BERT + Transformer)
- Social structure (via GCN on user-tweet graphs)

---

## Key Components

| Component        | Description |
|------------------|-------------|
| **BERT**         | Encodes tweet text into semantic embeddings |
| **Cosine Similarity** | Builds graph edges based on similarity |
| **GCN**          | Learns from the graph structure (user-post links) |
| **Transformer**  | Captures long-range, cross-node dependencies |

---

## Results

 **97% Recall on Fake Labels**  
 **Outperforms** SVM, XGBoost, and standalone GCN  
 Handles **imbalanced data** and misinformation propagation

---

##  Repository Contents

- `GCN&GCNTransformer.ipynb` – Main model architecture + training
- `EDA_MLandDL.ipynb` – Exploratory analysis + traditional models
- `GCN-Transformer_thesis.pdf` – Full MSc thesis
- `requirements.txt` – Required Python packages

---

##  Dataset

Uses the open-source **Twitter 15/16** datasets  
Includes real/false labels, tweet content, and user interactions

---

<p align="center">
  <img src="https://img.shields.io/badge/python-3.10-blue" />
  <img src="https://img.shields.io/badge/BERT-transformer-green" />
  <img src="https://img.shields.io/badge/GCN-graph--learning-red" />
</p>

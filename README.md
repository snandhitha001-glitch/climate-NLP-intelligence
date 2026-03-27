# Climate NLP Intelligence
AI-driven analysis of climate disclosures & social media using NLP, transfer learning, and sequence tagging.

## Overview
This project explores how **Natural Language Processing (NLP)** can be applied to extract actionable insights from **climate-related textual data**, spanning both **corporate disclosures** and **social media streams**.

It combines **sentiment classification, topic modeling, and named entity recognition (NER)** to build an end-to-end understanding of how climate risks and opportunities are communicated across different domains.

The work is grounded in real-world datasets including **ClimateBERT** and the **Broad Twitter Corpus (BTC)**, and emphasizes **model comparison, interpretability, and performance evaluation**.

## Key Objectives
* Classify climate-related text into **Risk, Opportunity, or Neutral sentiment**
* Compare **traditional ML vs transformer-based approaches**
* Identify **latent topics driving climate narratives**
* Build a **Named Entity Recognition (NER)** system for unstructured Twitter data
* Evaluate models using **robust metrics and error analysis**

## Methodology
1. **Climate Sentiment Classification**
* Implemented and compared multiple models:
  * **Naïve Bayes (custom-enhanced)**
  * **Machine Learning baselines**
  * **Transformer-based models (ClimateBERT-inspired approach)**
* Key enhancements:
  * Feature engineering improvements to baseline classifiers
  * Exploration of **transfer learning for domain-specific NLP**
* Evaluation:
  * Accuracy, Precision, Recall, F1-score
  * Comparative performance analysis across models
  * Misclassification diagnostics to identify failure patterns

2. **Topic Modeling for Climate Narratives**
* Extracted themes associated with:
  * Climate **risks**
  * Climate **opportunities**
* Techniques explored:
  * Probabilistic topic modeling (e.g., LDA variants)
  * Parameter tuning and preprocessing variations
* Outputs:
  * Interpretable topic clusters
  * Visualization of dominant themes
  * Comparative analysis of modeling approaches
* Insight focus:
  * How businesses frame **climate risk vs opportunity narratives**

3. **Named Entity Recognition (NER) on Twitter Data**
* Built a **sequence tagging model** on the BTC dataset
* Designed to extract:
  * **Persons**
  * **Organizations**
  * **Locations**
* Key components:
  * Tokenization strategy & tag alignment
  * Feature engineering / model architecture design
  * Sequence labeling using BIO tagging format
* Evaluation:
  * Entity-level Precision, Recall, F1-score
  * Error analysis on mislabelled entities
  * Identification of domain-specific challenges (e.g., noisy text)

 ## Key Insights
* **Transformer-based models significantly outperform traditional methods**, highlighting the impact of **domain-adaptive pretraining (ClimateBERT)**
* Climate discourse shows **distinct thematic separation** between risk (regulation, emissions, liabilities) and opportunity (innovation, sustainability, investment)
* NER performance is **sensitive to informal language**, with errors concentrated in:
  * Ambiguous entities
  * Hashtags and abbreviations
* Model performance improves with **better preprocessing and contextual embeddings**, but interpretability trade-offs remain

## Tech Stack
* Languages & Tools: Python, Jupyter Notebook
* Libraries:
  * NLP: HuggingFace Transformers, NLTK, SpaCy
  * ML: Scikit-learn
  * Topic Modeling: Gensim
  * Data Handling: Pandas, NumPy
  * Visualization: Matplotlib, Seaborn
 
## What This Project Demonstrates
* End-to-end **NLP pipeline design**
* Ability to **compare classical ML and modern transformer models**
* Strong understanding of:
  * **Transfer learning in NLP**
  * **Sequence tagging architectures**
  * **Topic modeling limitations**
* Focus on **interpretability, evaluation, and real-world applicability**

## Summary
This project demonstrates how AI can transform unstructured climate data into structured, decision-relevant insights, bridging the gap between raw text and strategic intelligence.

## Author 
Nandhitha Sivakumar

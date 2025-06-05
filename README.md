GBERT-Based Text Classifiers: Institutional Domains & Tech Sentiment
This repository provides two fine-tuned GBERT-base models for German-language text classification tasks:

Institutional Domain Classification (5 classes)

Tech Sentiment Classification (3 classes)

🔍 Overview
These models are based on the GBERT-base model by Chan et al. (2020), available here:
👉 deepset/gbert-base on Hugging Face

The fine-tuned models are trained to perform the following tasks:

1. Institutional Domain Classifier
Classifies texts into one of five domains:
Economy
Policy
Security
Science
Society

2. Tech Sentiment Classifier
Classifies texts into one of three technology sentiment categories:
Pro-tech
Tech-neutral
Anti-tech

📦 Releases
The fine-tuned models can be downloaded under the Releases section of this repository:

institutional_domain_model.zip

tech_sentiment_model.zip

📊 Training Data
This repository also includes manually labeled training datasets:

speeches_labeled_institutional domains.csv – for domain classification

speeches_labeled_tech sentiment.csv – for sentiment classification

🤝 Intercoder Reliability Data
A sample of 250 speeches was manually labeled by Coder A and Coder B to assess intercoder reliability. These are also included in the repository:

intercoder_sample.csv

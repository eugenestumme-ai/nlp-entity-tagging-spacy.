# NLP Named Entity Recognition (NER) & BIO Tagging

Comparative analysis of manual BIO schema annotation versus automated spaCy model outputs (`en_core_web_sm`) on financial news text, developed for AIM 350 coursework.

## 🚀 Project Overview
This project explores Natural Language Processing (NLP) tokenization and Named Entity Recognition (NER). It evaluates how manual text annotation aligns with automated machine learning pipelines when extracting named entities (persons, organizations) from financial commentary.

## 🔑 Key Components & Methodology
* **Source Selection:** Analyzed an Associated Press financial news article covering Federal Reserve interest rates and sticky inflation.
* **Manual BIO Annotation:** Hand-tagged a 19-word sentence token-by-token using the standard Begin-Inside-Outside (BIO) schema:
  * *Example:* `Joe` (B-PERSON), `Brusuelas` (I-PERSON), `RSM` (B-ORG).
* **Automated spaCy Pipeline Extraction:** Processed the same sentence using spaCy's `en_core_web_sm` model to extract Part-of-Speech (POS) tags and automated NER labels.
* **Comparative & Contextual Analysis:** Evaluated alignment between human annotations and model predictions, assessing how statistical models handle professional titles versus rigid named entity classifications.

## 🛠️ Tech Stack & Concepts
* **NLP Framework:** spaCy (`en_core_web_sm`)
* **Annotation Standards:** BIO Schema, POS Tagging, Tokenization
* **Domain:** Financial News / Economic Analysis

---
*Created by Eugene Stumme | [GitHub Profile](https://github.com/eugenestumme-ai)*

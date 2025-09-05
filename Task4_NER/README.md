# Task 4 - Named Entity Recognition (NER) from News Articles

## 📌 Description
Perform Named Entity Recognition (NER) on news articles using SpaCy.  
Entities like **people, organizations, and locations** are extracted and categorized.  

## 🔧 Steps
1. Load dataset (CoNLL-2003 or sample news text).
2. Apply SpaCy NER with:
   - `en_core_web_sm` (small model)
   - `en_core_web_lg` (large model)
3. Compare performance of different models.
4. Highlight entities in text with displacy.

## 📂 Project Structure
Task4_NER/
│── ner_analysis.ipynb
│── requirements.txt
│── README.md
│── data/
│ └── conll2003_sample.txt
│── outputs/
│ └── displacy_example.html
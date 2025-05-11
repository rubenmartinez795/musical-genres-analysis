# A Comparative Analysis of Song Lyrics Across Musical Genres

This repository contains the code and data necessary to reproduce the experiments presented in the article:

**A Comparative Analysis of Song Lyrics Across Musical Genres**  
Rubén Martínez and Carlos Alarcón  
University of Cantabria, Spain

---

## Abstract

This study presents a computational linguistic analysis of song lyrics across pop, rap, rock, country, and R&B genres to identify distinctive linguistic signatures. Employing natural language processing techniques on a corpus of 10,000 songs, we examine multiple dimensions including vocabulary usage, stylistic features, parts of speech distribution, and sentiment patterns. Our findings reveal significant cross-genre variations: rap lyrics demonstrate superior lexical diversity and noun usage; rock lyrics favor certainty markers and balanced sentiment; country lyrics show elevated past-tense usage and positive sentiment; R&B features prominence of pronouns and emotional expression; while pop maintains moderate values across most metrics. These linguistic patterns prove sufficiently distinctive to enable genre classification with 49% accuracy using a Naive Bayes classifier—significantly above random baseline. Modal verbs emerge as unexpectedly powerful discriminators, with *will* usage 18.2 times more likely in rock than rap lyrics. The research quantifies how different musical traditions employ language as an artistic medium, reflecting distinct cultural and aesthetic sensibilities that extend beyond mere semantic content.

---

## Reproducing the Experiments

To reproduce all experiments in the article:

1. Clone the repository:
   ```bash
   git clone https://github.com/rubenmartinez795/musical-genres-analysis.git
   cd musical-genres-analysis
   ```

2. Open and run the Jupyter notebook:
   ```
   lyrics.ipynb
   ```

This notebook executes all steps: data loading, feature extraction, analysis, and classification.

---


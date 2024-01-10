# Legal Cases Text Summarization

## Introduction
Legal cases text summarization plays a pivotal role in aiding legal professionals to efficiently navigate an expanding volume of case law. By condensing lengthy and intricate legal texts into concise summaries, this technique enables quicker access to crucial information, facilitates thorough research, and assists in the extraction of key insights and precedents, saving time and enhancing decision-making processes within the legal domain.

## Problem Definition
The study aims to improve the efficiency of Natural Language Processing (NLP) techniques for summarizing legal texts, utilizing the UCI legal corpus, and evaluating the accuracy of these methods using the ROUGE metric, ultimately contributing to the development of more effective tools for legal professionals dealing with vast amounts of case law.

## Data Overview
Dataset: https://archive.ics.uci.edu/dataset/239/legal+case+reports

The dataset contains Australian legal cases from the Federal Court (FCA) downloaded from AustLII for the years 2006 to 2009. It's tailored for testing automatic summarization and citation analysis. Each document includes catchphrases, citation sentences, citation catchphrases, and citation classes, providing valuable material for summarization experiments and understanding case citations.

## Preprocessing
Preprocessing involved extracting crucial information like case names, catchphrases, sentences, and citations from XML files. Cleaning steps included removing non-letter characters and punctuation while normalizing whitespaces, ensuring data consistency for subsequent text summarization tasks.

## Classification Models
We explored several classification algorithms to predict genres:
* SumBasics
* KL Divergence
* TextRank
* Neural Network-based Sentence Extraction
* Bidirectional Encoder Representations from Transformers

## Model Performance
We use the ROUGE (Recall-Oriented Understudy for Gisting Evaluation) metric to measure the quality of the generated summaries in comparison to the human-authored summaries.
  
## Conclusion
This project showcases the power of audio features in generating legal case summaries. By leveraging machine learning techniques, we successfully built accurate models for text summarization. 


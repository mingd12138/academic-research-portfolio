# 02 | MSc Dissertation — Linguistic Style, Sentiment and NLP in WIRED

**Full dissertation:** [Read the original PDF](Linguistic%20Style%20and%20Sentiment%20Analysis%20of%20Libertarianism%20in%20Cyberspace%20at%20WIRED%20Magazine%20Based%20on%20Natural%20Language%20Processing.pdf)  
**Institution:** Durham University  
**Degree:** Master of Data Science  
**Submission:** September 2024  
**Research type:** Completed MSc dissertation

## Research focus

*Linguistic Style and Sentiment Analysis of Libertarianism in Cyberspace at WIRED Magazine Based on Natural Language Processing* examines how themes, linguistic characteristics and sentiment associated with libertarianism in cyberspace appear in WIRED magazine articles, including variation across topics and time.

The project combines exploratory linguistic analysis, topic modelling, lexicon-based sentiment analysis and experiments with emotion-classification methods.

## Data and analysis

- Gathered and consolidated archived WIRED article records sourced through ProQuest, with material covering approximately 2008–2024.
- Applied keyword screening to identify **2,466 potentially relevant records** from a larger working corpus of approximately 4,000 records.
- Prepared text for NLP analysis, including cleaning and preprocessing.
- Examined linguistic characteristics and thematic structure using exploratory analysis and **Latent Dirichlet Allocation (LDA)**.
- Applied **VADER** and **TextBlob** to investigate sentiment polarity.
- Explored emotion classification with methods including **Naive Bayes, SVM, CNN, LSTM and a BERT-based approach**, using labelled emotion data for model development and then analysing predictions on WIRED texts.

The full methodology, tables, figures and any code excerpts are documented in the [dissertation PDF](Linguistic%20Style%20and%20Sentiment%20Analysis%20of%20Libertarianism%20in%20Cyberspace%20at%20WIRED%20Magazine%20Based%20on%20Natural%20Language%20Processing.pdf).

## Findings reported in the dissertation

- The lexicon-based results indicated that positive sentiment appeared more frequently than negative sentiment in the selected texts, while varying across periods and themes.
- Topic modelling identified themes spanning technology, data applications, and social and cultural discussions.
- In the reported emotion-classification analysis, the CNN output covered more of the seven reported emotion categories than the LSTM and Transformer implementations used in this project; it was consequently used for further category-level examination.

## Methodological limitations

- **Corpus selection:** keyword choices influence what enters the analysis; the selected subset does not represent every possible discussion of libertarianism.
- **Data provenance:** archived records may have incomplete metadata or other limitations.
- **Domain shift:** results learned or evaluated on one labelled emotion dataset may not transfer reliably to WIRED articles.
- **Interpretation:** emotion-category definitions, sentiment lexicons and language context affect how automated outputs should be read.
- **Ground truth:** predicted emotion distributions alone cannot show which classifier is most accurate on target articles without suitable independent annotations.

These limitations are important to my subsequent interest in **evaluation validity, robustness and responsible interpretation of NLP outputs**.

## My contribution

I performed the corpus preparation and screening, NLP analyses, modelling experiments, comparison and interpretation of outputs, and dissertation writing.

## Repository availability

This repository contains the **submitted PDF**. Please refer to the PDF for detailed methods and references.

[Back to portfolio homepage](../README.md)
